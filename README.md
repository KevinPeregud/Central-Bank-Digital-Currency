# Central-Bank-Digital-Currency
This code defines a CBDC contract with the following features:

- `name` and `symbol` variables to define the name and symbol of the CBDC token
- `totalSupply` variable to keep track of the total supply of CBDC tokens
- `inflationRate` variable to define the annual inflation rate of the CBDC
- `interestRate` variable to define the annual interest rate of the CBDC
- `bondInterestRate` variable to define the annual interest rate of the CBDC bonds
- `bondMaturity` variable to define the maturity period of the CBDC bonds
- `stakingDuration` variable to define the staking period for staking rewards
- `stakingReward` variable to define the staking reward percentage
- `balanceOf` mapping to keep track of the balance of each CBDC holder
- `stakingBalance` mapping to keep track of the staking balance of each CBDC holder
- `stakingTime` mapping to keep track of the staking start time of each CBDC holder
- `bondBalance` mapping to keep track of the bond balance of each CBDC holder
- `bondMaturityTime` mapping to keep track of the bond maturity time of each CBDC holder
- `Transfer` event to emit when CBDC tokens are transferred
- `Staking` event to emit when CBDC tokens are staked
- `Unstaking` event to emit when CBDC tokens are unstaked
- `Bonding` event to emit when CBDC bonds are bought
- `Redeeming` event to emit when CBDC bonds are redeemed
- `constructor` function to initialize the total supply of CBDC tokens and assign them to the contract creator
- `transfer` function to transfer CBDC tokens from one holder to another
- `stake` function to stake CBDC tokens for staking rewards
- `unstake` function to unstake CBDC tokens and claim staking rewards
- `calculateStakingReward` function to calculate 
