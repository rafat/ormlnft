# orml-nft pallet : Enable NFT support.

Create Class

<img src="https://github.com/rafat/ormlnft/blob/main/img/create_class.jpg"/>

Mint Tokens

<img src="https://github.com/rafat/ormlnft/blob/main/img/mint.jpg"/>

types.json https://github.com/rafat/ormlnft/blob/main/substrate-node-template/types.json

```
{
  "Address": "AccountId",
  "LookupSource": "AccountId",
  "ClassId": "u64",
  "TokenId": "u64",
  "ClassData": "u32",
  "TokenData": "u32",
  "metadata": "Vec<u8>",
  "ClassInfo": {
    "metadata": "Vec<u8>",
    "total_issuance": "TokenId",
    "owner": "AccountId",
    "data": "ClassData"
  },
  "TokenInfo": {
    "metadata": "Vec<u8>",
    "owner": "AccountId",
    "data": "TokenData"
  },
  "ClassInfoOf": "ClassInfo",
  "TokenInfoOf": "TokenInfo"
}
```

