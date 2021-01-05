# Primitive Token Lists

## What are Token Lists?
https://tokenlists.org/

Token lists are an ERC20 token list standard developed by [Uniswap](https://uniswap.org). 

At Primitive, we are using token lists to bring order, clarity, and quality to the ever-expanding list of ERC20 tokens supported by the Primitive Interface. 
## What are Primitive Token Lists?

Primitive Token Lists are seperated into 3 distict, self-explanatory, catagories.

- primitive-crypto-assets
  - WBTC
  - WETH
- primitive-defi-tokens
  - YFI
  - UNI
  - SUSHI
  - AAVE
  - SNX
  - etc...
- primitive-derivatives (assets, tokens, commodities, Forex, volatility instruments)
    - iETH
    - sBTC
    - uGas
    - EVIX

These lists are used in within the Primitive Interface to provide a community driven, relevant catalog of active Primitive option markets supported by the application and protocol.
## How can I propose a revision?

If you wish to add a token to a Primitive Token List, please open a Pull Request on this repository using the following format. 
### Title
`[Add/Remove] [Token Name] ([Token Symbol]) to [List Name]`
### Description 
`Rationale for adding this token to Primitive.  Usecase, DEX volume, market cap, existing option deployment, etc..`

Token List revision Pull Requests *must* include the addition or removal of the token object in the relevant token list.  This requires ERC20 token metadata described in the token list specification.
