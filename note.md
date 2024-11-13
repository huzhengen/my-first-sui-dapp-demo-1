### command

```
cd move
cd counter
sui client faucet
sui client publish --skip-dependency-verification
sui client publish
sui client new-env --alias devnet --rpc https://fullnode.devnet.sui.io:443
sui client switch --env devnet
```

### testnet

[warn] Client/Server api version mismatch, client api version : 1.37.3, server api version : 1.37.2
UPDATING GIT DEPENDENCY https://gitee.com/MystenLabs/sui.git
INCLUDING DEPENDENCY Sui
INCLUDING DEPENDENCY MoveStdlib
BUILDING counter
Successfully verified dependencies on-chain against source.
Transaction Digest: 3i5Rjz5LTKRotyRSpDdm4ALdU4TYoYBvFeuWtv4HcVXD

https://testnet.suivision.xyz/txblock/3i5Rjz5LTKRotyRSpDdm4ALdU4TYoYBvFeuWtv4HcVXD

package: https://testnet.suivision.xyz/package/0x65446d4a122ee8538c14215b47c97c1c3a52b55c9aa8efee3348dd3404b19a96

0x65446d4a122ee8538c14215b47c97c1c3a52b55c9aa8efee3348dd3404b19a96

### devnet

[warn] Client/Server api version mismatch, client api version : 1.37.3, server api version : 1.38.0
UPDATING GIT DEPENDENCY https://gitee.com/MystenLabs/sui.git
INCLUDING DEPENDENCY Sui
INCLUDING DEPENDENCY MoveStdlib
BUILDING counter
Skipping dependency verification
Transaction Digest: 5GurPPNrjhVytSRhxjz4by9gchsZJARjBosYZkRB9DBn

https://devnet.suivision.xyz/txblock/5GurPPNrjhVytSRhxjz4by9gchsZJARjBosYZkRB9DBn

package

https://devnet.suivision.xyz/package/0x5103e986215dfb4b7aeb47d82631c935884ebb74574a72b13b877dc262097089