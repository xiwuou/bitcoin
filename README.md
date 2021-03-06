# bitcoin

## 说明
这是基于区块链的学习，使用Go语言开发的私有区块链，旨在了解区块链的逻辑。
咱们的目的是了解其背后的技术原理，而不是“挖矿”或者“炒币”。

## 环境
go version >= 1.18

## 笔记
哈希算法并不是加密算法，它是提取数据的特征值进行计算，
其结果是不可逆的，即无法恢复原始数据。哈希算法具有：不可逆、唯一性、防篡改的特点。

对于数据库（例如MySQL）有唯一键，可以使用int自增，纯数字是可被预料的，哈希值不能被预料。
uuid作为主键也不可预料、唯一、不可逆。要让相同的数据计算后得到相同的值，用来验证数据的准确性，
证明你算力的工作量，MD5也可以，只是比特币选择了SHA256而已。

所以在我看来，计算哈希值的过程除了浪费电力、浪费计算机性能、产生温室气体外，不能说毫无意义，
只能说没啥软用。有用的可能就是比特币的价值了，燃烧你的GPU，韭菜成熟了就割一波，再长再割，
到头来不过还是资本的游戏。
