## Static analyzers
For more reference of integrating static anlyzers and foundry:

### Slither

https://book.getfoundry.sh/config/static-analyzers#slither

    pip3 install slither-analyzer
    pip3 install solc-select
    solc-select install 0.8.14
    solc-select use 0.8.14
    slither <path/to/contract.sol>

Configuration file: `slither.config.json`:


### Mithril 

https://book.getfoundry.sh/config/static-analyzers#mythril

Configuration file: `mythril.config.json`:

    rustup default nightly
    pip3 install mythril
    myth analyze src/Contract.sol --solc-json mythril.config.json



## Environment variables
It is recommended to have the following environment variables setup (perhaps in .bashrc):

    export MAINNET_RPC_URL="https://mainnet.infura.io/v3/..............."
    export GOERLI_RPC_URL="https://goerli.infura.io/v3/..............."
    export RINKEBY_RPC_URL="https://rinkeby.infura.io/v3/..............."
    export POLYGON_RPC_URL="https://polygon-mainnet.infura.io/v3/..............."
    export ARBITRUM_RPC_URL="https://arbitrum-mainnet.infura.io/v3/..............."
    export OPTIMISM_RPC_URL="https://optimism-mainnet.infura.io/v3/..............."
    
    export ETHERSCAN_TOKEN="...................................."
    export BSCSCAN_TOKEN="...................................."
    export POLYGONSCAN_TOKEN="...................................."
    
    export DEV00_PRIVATE_KEY="....................................................."
    export DEV01_PRIVATE_KEY="....................................................."
    export DEV02_PRIVATE_KEY="....................................................."
    export DEV03_PRIVATE_KEY="....................................................."
    export DEV04_PRIVATE_KEY="....................................................."
    export DEV05_PRIVATE_KEY="....................................................."
    export DEV06_PRIVATE_KEY="....................................................."
    export DEV07_PRIVATE_KEY="....................................................."
    export DEV08_PRIVATE_KEY="....................................................."
    export DEV09_PRIVATE_KEY="....................................................."
