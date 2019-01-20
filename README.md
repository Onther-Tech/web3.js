# Plasma EVM JavaScript API

For the sake of convenience to migrate truffle, below apis are implemented in `web3.eth`, instead of `web3.pls`.


### Plasma EVM APIs

#### web3.eth.rootchain

```web3.eth.rootchain()```

Get the address of RootChain contract deployed in root chain.


##### Examples
```javascript
var rootchain = web3.eth.rootchain()
console.log(rootchain) // "0x880ec53af800b5cd051531672ef4fc4de233bd5d"
```

#### web3.eth.getRequestableContract

```web3.eth.getRequestableContract(requestableContractInRootChain)```

Get the address of requestable contract in child chain.

##### Parameters
1. `String` - THe requestable contract address to query.

##### Examples
```javascript
`web3.eth.getRequestableContract(requestableContractInRootChain)`
```
