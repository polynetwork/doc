# [MainNet](README.md) | [TestNet](README_TestNet.md) | DevNet

This's cross chain asset contract info ONLY in <strong>DevNet</strong> mode, it's used to bind asset mapping in different chain, if the name ends with (s) on behalf of the asset is mapping.

## Btc

BTCx Redeem Script: 
- 522103c4564b837674de2482961a8d5f2a24a7e11e8a97aac5e92ac2e64500219144512102ccc07d3df7da58bb6fa5cfe5d7be415ff9463171b2600c93c080fcd0d49576a721036ec6299c1b14e57b45f1ad85eecbc48ad5447a05158a1bfb2ffb689ad69490d353ae

BTCx Redeem Key: 
- c737784e5fdae8860fb461d4d30ffd0b34701d5a

## Ethereum

Type | Contract Hash | Desc
---|---|---
CCMP | 0x7087E66D6874899A331b926C261fa5059328d95F |
Lock Proxy | 0x46DE64740cf839374afB264970f8D437732649cA |
ERC20 | 0x94566DB0987EcC816817F43d24E9d6bf29316392 |
OEP4x | 0x836c1Ad794F66A1a323567ae635D0Ce66Ed045D5 |
ONGx | 0xfC89307C880B203894cc7e1193fBf0bebd62c233 |
ONTx | 0xc0Be30D534e00bd485e10688023c9Cd9D523eEF0 |
ETH | 0x0000000000000000000000000000000000000000 |
BTCx | TODO | 
NEOx |  | not including in the testing framework

## Ontology

Type | Contract Hash | Desc
---|---|---
Lock Proxy | B: ebad45b887c6bf7cc4c1df8f72da156bc91b04b7 </br> L: b7041bc96b15da728fdfc1c47cbfc687b845adeb |
ERC20x | B: 2bd086d90c282a26d021d01039b84a968ed57444 </br> L: 4474d58e964ab83910d021d0262a280cd986d02b |
OEP4 | B: d6967fa9b11b0836ec9dc8572f4bab6f65d710f9 </br> L: f910d7656fab4b2f57c89dec36081bb1a97f96d6 |
ONG | B: 0200000000000000000000000000000000000000 </br> L: 0000000000000000000000000000000000000002 |
ONT | B: 0100000000000000000000000000000000000000 </br> L: 0000000000000000000000000000000000000001 |
ETHx | B: d6b4cd930377e7e81d1ace85bbb9ce59f4dd9410 </br> L: 1094ddf459ceb9bb85ce1a1de8e7770393cdb4d6 |
BTCx | B: d177d904456479dd592d4ce368e5d97ec8ffbcee </br> L: eebcffc87ed9e568e34c2d59dd79644504d977d1 |
NEOx | B:  </br> L: | not including in the testing framework

## Neo Legacy

Type | Contract Hash | Desc
---|---|---
pnUSDT | B:  0x20bc5bbb4dde06e5ca02bef761a9fdca6a05fd77 L: 77fd056acafda961f7be02cae506de4dbb5bbc20 |
CCMC | B: 0x3135a1a4668688a3e15b004af3a718f2d67141ca  </br> L: ca4171d6f218a7f34a005be1a3888666a4a13531 |
Lock Proxy | B: 0x3fef7ac6598ad83f5e4d4338e65530eba2173294 </br> L: 943217a2eb3055e638434d5e3fd88a59c67aef3f |

Receiver: A: AZXRTygHgRbPu9o16K6en4BaZD11tXCmN1 B: 0x4fd83a49df40c0a7de2671da20c2a8dfe495b6c2 L: c2b695e4dfa8c220da7126dea7c040df493ad84f

## Note 
`B` means big-endian, we can search the contract transaction history in corresponding explorer.

`L` means little-endian, we usually use it as the asset hash input when we do binding asset hash operation.

## Neo N3

Type | Contract Hash | Desc
---|---|---
pnUSDT | B:  0xc9505566e11660d239d987b5522a2232665bd0a8 L: a8d05b6632222a52b587d939d26016e1665550c9 |
CCMC | B: 0x7c842f3900ceba5bcdeeeec05c9b41ba63ad6cd2  </br> L: d26cad63ba419b5cc0eeeecd5bbace00392f847c |
Lock Proxy | B: 0x5376f41082a84fb000c944b6d44ba85b14e20fe5 </br> L: e50fe2145ba84bd4b644c900b04fa88210f47653 |

Receiver: A: NLKpYEDmyGMWQVeqcoyZr9Lyo8P5Mrozba B: 0x67ce818168a75d3bedb7d295bf11c060d1c38204 L: 0482c3d160c011bf95d2b7ed3b5da7688181ce67

## Note 
`B` means big-endian, we can search the contract transaction history in corresponding explorer.

`L` means little-endian, we usually use it as the asset hash input when we do binding asset hash operation.

## Cosmos-Gaia

Type | Denom (coin name) | Asset/Contract Hash | Desc
:-:|:-:|:-:|:-:
Lock Proxy | | f71b55ef55cedc91fd007f7a9ba386ec978f3aa8 |
ERC20 | erc20x | 657263323078 |
OEP4x | oep4x | 6f65703478 |
ONGx | ongx | 6f6e6778 |
ONTx | ontx | 6f6e7478 |
ETHx | ethx | 65746878 |
BTCx | btcx | 62746378 |
NEOx | neox | 6e656f78 | not including in the testing framework
GASx | gasx | 67617378 | not including in the testing framework
Cosmos| stake | 7374616b65 | not including in the testing framework


## Router And ChainId
Type | Router Number | ChainId
:-:|:-:|:-:
Bitcoin | 1 | 1
Ethereum | 2 | 2
Ontology | 3 | 3
NEO Legacy | 217 | 217
NEO N3 | 220 | 220
Cosmos-gaia | 5 | 8
Switcheo | 5 | 182
