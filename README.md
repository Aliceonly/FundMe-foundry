forge Forked Tests

1. Unit: Testing a single function
2. Integration: Testing multiple functions
3. Forked: Testing on a forked network
4. Staging: Testing on a live network (testnet or mainnet)

Mocking:
// 1.Deploy mocks when we are on a local anvil chain
// 2.Keep track of contract address across different chains

Fork Test:
创造HelperConfig.sol通过new NetworkConfig通过block.chainid进行跨链判断
传入不同网络的PriceFeed地址

Magic Number : init number above contract

引入modifier用于测试