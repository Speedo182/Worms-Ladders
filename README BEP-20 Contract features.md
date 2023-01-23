The BEP-20 smart contract for the Worms & Ladders Token includes the following features:

It inherits the functionality of Binance's BEP20 token standard, which includes basic functionality such as transfer, approve, and transferFrom.
It has a public name, symbol, and decimal variables, which store the name, symbol and number of decimal places of the token respectively.
It has a public totalSupply variable, which stores the total supply of the token.
It has a mapping of addresses to their token balance, which is used to track the balance of each address.
The contract's constructor initializes the totalSupply of the token and assigns all tokens to the contract deployer.
The transfer, approve, and transferFrom functions are implemented to allow for token transfers to occur between addresses.
Events are emitted for each transfer, approval, and transferFrom action, allowing for easy tracking of token transactions.
The implemented functions have basic error handling, to ensure that the transactions are only executed under certain conditions, like validating the address, the value of the token, and the allowance of the spender.
