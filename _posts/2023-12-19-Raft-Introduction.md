## In Search of an Understandable Consensus Algorithm
### Abstract

Raft 是一个用于管理重复记录的一致性算法。它达成的结果类似于Paxos算法，并且同样的高效，但是具有一个更易理解的结构。这会更有利于建立一个实际的系统。   
为了增强可理解性，Raft拆分了一致性算法中的多个关键元素，例如 leader election, log relication, safety. 并且它强制采取一种更强程度的内聚减少了需要考虑的状态总数。一份用户调研显示，对于学生来说，Raft比Paxos更易学。   
Raft 也提供一种新的改变集群成员的机制，该机制通过重叠大多数来保证安全性

### Introducation
