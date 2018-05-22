# CI Truffle Box

<div>

[![Build Status](https://travis-ci.org/NFhbar/truffle-ci-box.svg?branch=master)](https://travis-ci.org/NFhbar/truffle-ci-box)
[![Coverage Status](https://coveralls.io/repos/github/NFhbar/truffle-ci-box/badge.svg?branch=master)](https://coveralls.io/github/NFhbar/truffle-ci-box-faucet?branch=master)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/NFhbar/truffle-ci-box/pulls)

</div>

This box comes with everything you need to start a truffle project with Travis-ci and Coveralls integration. It also includes solium, eslint, and several common testing helpers.

## Instalation

1. Install Truffle and Ganache CLI globally.
    ```javascript
    npm install -g truffle
    npm install -g ganache-cli
    ```
2. Download the box.
    ```javascript
    truffle unbox integration-box
    ```
3. Create a `.env` file in the root directory and add your private key.
    ```
    RINKEBY_PRIVATE_KEY="MyPrivateKeyHere..."
    ROPSTEN_PRIVATE_KEY="MyPrivateKeyHere..."
    ```
    If you don't have a private key, you can use one provided by Ganache (for development only!):
    ```
    RINKEBY_PRIVATE_KEY="c87509a1c067bbde78beb793e6fa76530b6382a4c0241e5e4a9ec0a0f44dc0d3"
    ROPSTEN_PRIVATE_KEY="c87509a1c067bbde78beb793e6fa76530b6382a4c0241e5e4a9ec0a0f44dc0d3"
```
4. Update the Travis and Coveralls badges in the `README` file to point to your own repository.

5. Change any lint or solium rules that you like, and feel free to modifify the scripts or anything else you want!
