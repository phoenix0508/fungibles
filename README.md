# Fungibles

---

## 【Introduction of Fungibles】

-   Implement Minting of Fungibles NFT.
-   Implement NFT market place for simple trade by `buy/sell`

&nbsp;

---

## 【Setup】

### Setup private network by using Ganache-CLI

1. Download Ganache-CLI from link below  
   https://www.trufflesuite.com/ganache

2. Execute Ganache

```
$ ganache-cli -d
```

※ `-d` option is the option in order to be able to use same address on Ganache-CLI every time.

&nbsp;

### Setup wallet by using Metamask

1. Add MetaMask to browser (Chrome or FireFox or Opera or Brave)  
   https://metamask.io/

2. Adjust appropriate newwork below

```
http://127.0.0.1:8545
```

&nbsp;

### Setup backend

1. Deploy contracts to private network of Ganache

```
(root directory)

$ npm run migrate:local
```
