# teachbitcoin-cn

https://teachbitcoin.io 的教学 PPT 翻译。配合 libbitcoin 进行 比特币 原理&编程 教学。

> [Libbitcoin](https://github.com/libbitcoin/libbitcoin-system) 是一个异步的 C++ 比特币代码库. [相关文档](https://github.com/jachiang/LibbitcoinDocumentation).

## 内容
| 原文章节 | 简介 | 练习代码 | 译文章节 |
| - | - | - | - |
| [椭圆曲线数学](https://teachbitcoin.io/presentations/ec_math.html) | This chapter covers prime fields, elliptic curves operations over real numbers and prime fields.<br>These are the basic mathematical concepts that ECDSA signing is based on. | [代码](https://github.com/teachbitcoin/code-demos/tree/master/00_ec_math) | [进行中](https://chrislinn.github.io/teachbitcoin-cn/ec_math.html) |
| [DER 签名](https://teachbitcoin.io/presentations/ecdsa.html) | 比特币签名使用椭圆曲线签名算法 (Elliptic Curve Digital Signing Algorithm, ECDSA) 来为未花费输出 (unspent outputs) 提供安全性，并以 DER 序列化格式进行被编码。 | 无 | [__已完成__](https://chrislinn.github.io/teachbitcoin-cn/ecdsa.html) |
| [Addresses and HD Wallets](https://teachbitcoin.io/presentations/walltes.html) | Bitcoin addresses encode the information required for a wallet to spend to the correct key. Hierarchical Deterministic wallets use a child-key derivation algorithm to safely derive new addresses from the same root. | [代码](https://github.com/teachbitcoin/code-demos/tree/master/02_addresses_hd_wallets) | [进行中](https://chrislinn.github.io/teachbitcoin-cn/walltes.html) |
| [Introduction to Transactions](https://teachbitcoin.io/presentations/transaction_build.html) | An introduction to building and signing your first transaction which spends to Pay-to-Public-Key-Hash outputs. | [代码](https://github.com/teachbitcoin/code-demos/tree/master/03_transactions_introduction) | [进行中](https://chrislinn.github.io/teachbitcoin-cn/transaction_build.html) |
| [Signature Hash Modifiers](https://teachbitcoin.io/presentations/transaction_sighash.html) | Signatures can commit to specific input and outputs, allowing other parts of the transaction to be modified by other parties. | [代码](https://github.com/teachbitcoin/code-demos/tree/master/04_transactions_sighash_modifiers) | [进行中](https://chrislinn.github.io/teachbitcoin-cn/transaction_sighash.html) |
| [Multisignature Scripts](https://teachbitcoin.io/presentations/transaction_multisig.html) | An output script which can be spent by n-of-m signatures. | [代码](https://github.com/teachbitcoin/code-demos/tree/master/05_transactions_p2sh_multisig) | [进行中](https://chrislinn.github.io/teachbitcoin-cn/transaction_multisig.html) |
| [Pay-to-Script-Hash Scripts](https://teachbitcoin.io/presentations/transaction_p2sh.html) | P2SH output scripts commit to a hashed locking script. The locking script preimage must be provided together with the unlocking script for such a P2SH output to be spent. | [代码](https://github.com/teachbitcoin/code-demos/tree/master/05_transactions_p2sh_multisig) | [进行中](https://chrislinn.github.io/teachbitcoin-cn/transaction_p2sh.html) |
| [Transaction Timelocks](https://teachbitcoin.io/presentations/transaction_timelocks.html) | Absolute and relative timelocks prevent transactions from being broadcast before a certain time or blockheight. A timelock may be commited to by the transaction signature, or can be enforced by the previous output script. | [代码](https://github.com/teachbitcoin/code-demos/tree/master/06_transactions_timelocks) | [进行中](https://chrislinn.github.io/teachbitcoin-cn/transaction_timelocks.html) |
| [Witness Transactions](https://teachbitcoin.io/presentations/transaction_witness.html) | Pay-to-witness output scripts are be spent with transactions with valid witnesses. Wallets which do not support native P2W transactions may send to outputs which wrap P2W scripts in P2SH outputs. | [代码](https://github.com/teachbitcoin/code-demos/tree/master/08_transactions_witness) | [进行中](https://chrislinn.github.io/teachbitcoin-cn/transaction_witness.html) |
| [Block Chain](https://teachbitcoin.io/presentations/blockchain.html) | A closer lock at blocks and block headers, and their validation by nodes. | [代码](https://github.com/teachbitcoin/code-demos/tree/master/09_block_parsing) | [进行中](https://chrislinn.github.io/teachbitcoin-cn/blockchain.html) |
| [P2P Network](https://teachbitcoin.io/presentations/p2p.html) | An introduction to the P2P messaging protocol between Bitcoin nodes on the network. | [代码](https://github.com/teachbitcoin/code-demos/tree/master/10_p2p) | [进行中](https://chrislinn.github.io/teachbitcoin-cn/p2p.html) |
| [Simplified Payment Verification](https://teachbitcoin.io/presentations/spv.html) | SPV clients follow the longest header chain with the most proof-of-work. They rely on specific transaction updates from full Bitcoin nodes, and perform merkle proofs to validate confirmation of these transactions. | [代码](https://github.com/teachbitcoin/code-demos/tree/master/11_simplified_payment_verification) | [进行中](https://chrislinn.github.io/teachbitcoin-cn/spv.html) |
| [Payment Channels and Lightning Network](https://teachbitcoin.io/presentations/payment_channels.html) | We demonstrate a basic payment channel between two nodes which is enabled by revocable output scripts (RSMC's). Payment routing across multiple payment channels is made possible by hashed time-locked contracts (HTLC's). | [代码](https://github.com/teachbitcoin/code-demos/tree/master/12_payment_channels) | [进行中](https://chrislinn.github.io/teachbitcoin-cn/payment_channels.html) |

相关编程代码和讲解/指南可在[这里](https://github.com/teachbitcoin/code-demos)找到。

## 致谢
+ https://github.com/teachbitcoin
+ https://github.com/libbitcoin
+ https://github.com/jachiang
+ https://github.com/liushooter
