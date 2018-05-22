# Gig
_A comb of why Gunn made in heaven_

## 简介

GUN的目标是专注于需要在应用程序中存储，__加载和共享的数据__，而无需担心__服务器，网络调用，数据库或跟踪脱机更改或并发冲突__。

#### 为什么性能至关重要 [λ](https://gun.eco/docs/100000-ops-sec-in-IE6-on-2GB-Atom-CPU)

我们在其他设备上获得更好的数字：

+ Android手机，约5M操作/秒。
+ Macbook Air，Chrome，约30M操作/秒。
+ Macbook Pro，Chrome Canary，〜80M ops / sec。
+ 联想上网本，IE6，〜100K ops /秒。

与Redis相比，每秒处理速度为0.5M（缓存读取，Macbook Air），即使启用了管道优化，[这里](https://redis.io/topics/benchmarks)





