# spark

    在cf包中，使用spark实现了item-based协同过滤和user-based协同过滤。
在协同过滤中添加了一种新的相似度计算方式jacaard*cosine，此种相似度计
算方式在一定的场景中比较适用，当两个物品通过很少人进行连接时，使用
jacaard比较合适，但没有考虑到评分值，使用cosine时，相似度值又会偏大。
同时也对 rating 也做了少许改进。

    在 batchwriteDB包中，分享了批量写 redis 和 hbase的方式。

