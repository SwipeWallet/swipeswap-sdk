# Swipeswap SDK

In-depth documentation on this SDK is available at [uniswap.org](https://uniswap.org/docs/v2/SDK/getting-started/).

This modifies uniswap-sdk's UniswapV2Factory address. The new address for swipeswap is  `0x8a93B6865C4492fF17252219B87eA6920848EdC0`.

## Running tests

To run the tests, follow these steps. You must have at least node v10 and [yarn](https://yarnpkg.com/) installed.

First clone the repository:

```sh
git clone https://github.com/SwipeWallet/swipeswap-sdk.git
```

Move into the swipeswap-sdk working directory

```sh
cd swipeswap-sdk/
```

Install dependencies

```sh
yarn install
```

Run tests

```sh
yarn test
```

You should see output like the following:

```sh
yarn run v1.22.10
$ tsdx test
 PASS  test/route.test.ts
 PASS  test/fraction.test.ts
 PASS  test/miscellaneous.test.ts
 PASS  test/router.test.ts
 PASS  test/pair.test.ts
 PASS  test/token.test.ts
 PASS  test/trade.test.ts
 PASS  test/entities.test.ts

Test Suites: 2 skipped, 8 passed, 8 of 10 total
Tests:       4 skipped, 124 passed, 128 total
Snapshots:   0 total
Time:        4.497s
Ran all test suites.
✨  Done in 6.94s.
```
