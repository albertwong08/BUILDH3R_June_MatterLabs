# BUILDH3R_June_MatterLabs

This is my first experience to try out smart contract development on zkSync. 

The workshop consists of 2 parts:
1. Try out the quickstart session as mentioned at the zksync doc:
2. Build smart account contract to modify the Signature

I learnt smart contract development over ethereum before. Thus the first session is still manageable for me.

As suggested by the quickguide, I used Remix for the development

![image](https://github.com/albertwong08/BUILDH3R_June_MatterLabs/assets/80051495/804f03cf-7df9-4886-80a6-9f0da9d46546)

The smartcontract is a simple one: it stores the message as a string array. This message array is stored on chain. Thus the sendMessage function which add message to the array will trigger a transaction which charge gass fee
ps: to make the variable not stored on chain, use memory keyword when declare a variable.

https://sepolia.explorer.zksync.io/address/0xEba55e4151Ed4D665b0D1656E96C459C2Cb83a3e
![image](https://github.com/albertwong08/BUILDH3R_June_MatterLabs/assets/80051495/35383569-eb0e-4811-b5f8-7efc4007f4c2)

The second part is still a difficult part for me. It has a concept called Smart Account contract on zkSync. From development prospective, so far I know such contract implements a IAccount interface which requires implementation of both validateTransaction and executeTransaction functions. I think I will spend time studying the Smart Account contract which is interesting to me.

To sum up, it is quite an exciting experience help me do a revision on smart contract development with solidity, and learn a new thing called Smart Account. 
