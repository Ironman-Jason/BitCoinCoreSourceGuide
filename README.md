# BitCoinCoreSourceGuide
目标是分析比特币源代码，从系统启动流程，再到每个业务流的分析。
目前完成了部分的bitcoin daemon的启动流程，每周周五会更新一个版本。
用到的工具目前有：xmind。请安装xmind来阅读启动流程部分，并注意每个分支中的注解，里头保护有代码的功能介绍。

# 2PC-type consensus paper link
## PBFT
  http://pmg.csail.mit.edu/papers/osdi99.pdf    
  http://www.pmg.csail.mit.edu/papers/bft-tocs.pdf    
  [阅读时请自己提出批判性问题，去返推出作者观点。]
  http://www.cs.utah.edu/~stutsman/cs6963/public/pbft.pdf    
## RAFT
  [8010实验室的分布式数据库也用的类似与RAFT的算法，只不过在实现时只满足了80%的RAFT算法]
  https://raft.github.io/raft.pdf    
## Paxos
  http://www.scs.stanford.edu/~dm/home/papers/paxos.pdf    
  https://lamport.azurewebsites.net/pubs/lamport-paxos.pdf    
  https://lamport.azurewebsites.net/pubs/paxos-simple.pdf    
