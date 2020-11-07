# kafka
Kafka是一个开源的由scala语言写的分布式消息系统，最初是LinkedLIn公司设计的分布式提交日志系，之后成为了Apache的一部分。特性：
可扩展：水平热扩展
高吞吐，低延迟：消息顺序读写，zero-copy系统调用，topic->partition->segment file（数据分区，并行处理），message批处理压缩发送, 充分利用page cache提高IO效率
持久性：消息存磁盘并支持多副本
容错性：允许节点失败
高并发：支持多用户同时读写
## 基本结构


## Topic

### 创建流程
![Create Topic](https://github.com/XuanZhouGit/kafka/blob/master/CreateTopicFlow.JPG)
### 处理过程

