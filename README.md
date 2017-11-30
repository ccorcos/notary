# Ethereum Notary

Work in progress.

## Learning

- Learn about Ethereum.
	- [Introductory talk about what Ethereum is.](https://www.youtube.com/watch?v=66SaEDzlmP4&t=733s)
	- [Download the Ethereum Wallet (a.k.a Mist)](https://ethereum.org/)
		- Open it up and download the blockchain (may take a while).
		- Create an account and save your key somewhere save.
	- Get started with the Rinkeby Testnet so you can play with the Ethereum wallet without spending real Ether.
		- Connect the Ethereum Wallet to the test network: Develop > Network > Rinkeby -- Test Network
		- Create an account on Rinkeby and post your address on Twitter (Rinkeby does this to prevent spam) and post a link to that twitter account in [Rinkeby's Faucet](https://www.rinkeby.io/#faucet) to get some free Ether.
		- That Ether should show up in your account, and you can then play around with the Ethereum Wallet UI.
- Development
	- Read the Ethereum.org tutorials
		- [Coin contract](https://www.ethereum.org/token)
		- [Crowdsale contract](https://www.ethereum.org/crowdsale)
		- [Decentralized autonomouse organization contract](https://www.ethereum.org/dao)
	- [Read the truffle docs.](http://truffleframework.com/docs/)
	- [Skim the solidity docs.](http://solidity.readthedocs.io/en/develop/index.html)
	- Zeppelin
		- [Read the guides](https://blog.zeppelin.solutions/guides/home).
		- [Read the source code.](https://github.com/OpenZeppelin/zeppelin-solidity)
		- [Skim the Zeppelin docs.](http://zeppelin-solidity.readthedocs.io/en/latest/index.html)
	- [Explore the truffle boxes.](http://truffleframework.com/boxes/)
		- This truffle box has an [authentication contract](https://github.com/truffle-box/react-auth-box/blob/master/contracts/Authentication.sol) so you can [login through the Web UI](https://github.com/truffle-box/react-auth-box/blob/master/src/user/ui/loginbutton/LoginButtonActions.js#L36-L45).

## Development Notes

Install Truffle.

```
npm install -g truffle
```

You can start truffle from a "box".

```
truffle unbox metacoin
```

## To Do

- Compile and build everything.
- Deploy MetaCoin to Rinkeby using my Rinkeby account.
	 - How do I specify the account?
	 - Where is the address saved?
- Install Zeppelin.
- Build a simple notary?
	- Simple html webpage for now.

- Explore some of the tooling
	- https://www.ethereum.org/cli
	- http://web3js.readthedocs.io/en/1.0/index.html
		- Where is the truffle private key stored?
		- How can you iterate through the blockchain?
		- Can you view decompiled source code?
		- Can you view decompiled data structures?

## Getting Started

Coming soon...