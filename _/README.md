# <img src="header.png" alt="Freight Trust Smart Contracts" height="60px">
<br>

## Instructions:
1. Fork This Repository 
2. Create a New Branch named with your user name on Github
3. Create a new `nodeaddress.json` file
4. Make Sure your Node Address conforms to EIP-55.
5. Submit Pull Reuqest and await merge

## Freight Trust Network

| Class           | Value                                                                 |
|-----------------|-----------------------------------------------------------------------|
| Ethereum Wallet | 0x\.\.\.                                                              |
| Node Address    | 0x\.\.\.                                                              |
| Region          | USA, EURO\-\(FRA,GER,SWE,NEL,EU\), GBR, RTE, AUST, JAPN, AVAIL, OTHER |
| Node            | Signer, Validator, Authority, Heartbeat                               |
| Date            | 2020\-1\-2 23:59:59 \+0000                                            |
---
**Ethereum Wallet**: Your Ethereum Main Net Wallet Address
**Node Address**: Your Freight Trust Network. Generate your Node Address on your *personal computer* by running the command:
```bash 
$ bin/besu --data-path=data public-key export-address --to=data/nodeAddress
```
**Region**: The Geographic Region in which you are domiciled and will host the node.
GBR: Great Britian
RTE: Republic of Ireland
AUST: Australia 
JAPN: Japan
AVAIL: Whatever is Available
OTHER: Switerzland, India, Hong Kong, Tawiwan, South Korea, Brazil
**Node**: Leave this as-is. 
**Date**: Leave this as-is.

---
## Example

You ONLY create a NEW JSON File with your ETHEREUM WALLET ADDRESS.json as shown below. The table above is for informational purposes, the json file is the actual data. 

In this example we are signing up for operating a node in Europe.
Actual File saved as `0xC0BD37be44632C587F7466da478d363ff79d4F7A.json`
```json
{
  "user": "mer1dian",
  "provider": "aws/gcloud",
  "region": "EURO",
  "eth_address": "0xC0BD37be44632C587F7466da478d363ff79d4F7A",
  "ftn_address": "0x0026c1b0c4b2f856f23f71d1c9d8d7ae7885cb41",
  "node": "signer",
  "data": ""
}
```
## [Please CHECKSUM your NODE ADDRESS YOU GENERATE](https://piyolab.github.io/sushiether/RunScrapboxCode/?web3=1.0.0-beta.33&code=https://scrapbox.io/api/code/sushiether/web3.js_-_Ethereum_%E3%81%AE%E3%82%A2%E3%83%89%E3%83%AC%E3%82%B9%E3%82%92%E3%83%81%E3%82%A7%E3%83%83%E3%82%AF%E3%82%B5%E3%83%A0%E4%BB%98%E3%81%8D%E3%82%A2%E3%83%89%E3%83%AC%E3%82%B9%E3%81%AB%E5%A4%89%E6%8F%9B%E3%81%99%E3%82%8B/demo.js)

<br>
---
(c) 2019-2020 FreightTrust & Clearing Corporation
