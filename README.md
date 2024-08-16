# Token Lists

- Submit a PR or create a public repo
- Add or remove `tokens[]`
- `tokens` must have the following values:
  - name: string
  - address: string
  - symbol: string
  - decimals: number
  - chainId: number
  - logoURI: string

```json
"tokens": [
  {
    "name": "Token",
    "address": "0x58F375e1F2FA27a775Eb02745317089586D460cc",
    "symbol": "TKN",
    "decimals": 18,
    "chainId": 123123,
    "logoURI": "https://yourtokenlogo.com/icon.png"
  }
]
```

- [Verify JSON ](https://jsonlint.com/)
- Update version number

```json
"version": {
  "major": 1,
  "minor": 0,
  "patch": 1 <-----
},
```
