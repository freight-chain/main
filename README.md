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

> Information Used

| Class           | Value                                      |
|-----------------|--------------------------------------------|
| Ethereum Wallet | 0xC0BD37be44632C587F7466da478d363ff79d4F7A |
| Node Address    | 0x0026c1b0c4b2f856f23f71d1c9d8d7ae7885cb41 |
| Region          | EURO\-FRA                                  |
| Node            | Signer, Validator, Authority, Heartbeat    |
| Date            | 2020\-1\-2 23:59:59 \+0000                 |

In this example we are signing up for operating a node in Europe.
Actual File saved as `0xC0BD37be44632C587F7466da478d363ff79d4F7A.json`
```json
{
  "user": "mer1dian",
  "name": "Freight Trust Protocol",
  "region": "EURO",
  "eth_address": "0xC0BD37be44632C587F7466da478d363ff79d4F7A",
  "ftn_address": "0x0026c1b0c4b2f856f23f71d1c9d8d7ae7885cb41",
  "node": "signer",
  "data": ""
}
```


---
(c) 2019-2020 FreightTrust & Clearing Corporation