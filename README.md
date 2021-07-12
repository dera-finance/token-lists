# TokenList

This package includes Token icons and JSON metadata for token infos.

Anyone can create and maintain a token info, as long as they follow the specification.

## How to use

Raw: [https://raw.githubusercontent.com/dera-finance/token-lists/main/Tokens/RNA/logo.png](https://raw.githubusercontent.com/dera-finance/token-lists/main/Tokens/RNA/logo.png)
Proxied: [https://token.dera.finance/RNA/logo.png](https://token.dera.finance/RNA/logo.png)

## Contribution Rules

### Tokens

- Under `Tokens` folder
- Token address as folder name
- Icons in svg/png format are requied, icons naming logo.svg and logo.png are recommended.
- Json file is optional for detailed information

eg.

```sh
├── ./Tokens/0x000000000000000000000000000000000000c000
│   ├── logo.svg
│   └── logo.png
│   └── logo-alt.svg
│   └── logo-alt.png
│   └── info.json
```

### dApps

- Under `dApps` folder
- Domain name as folder name
- Recommend svg/png/ico files

eg.

```sh
├── ./dApps/dapp.domain
│   ├── logo.svg
│   └── icon.png
│   └── favicon.ico
```
