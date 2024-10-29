# Readme
A note about Message Queue Task.

### Message Queue Task
Message Queue Task是Remote Mutex Lock的一种替代方案，其通过限制只能有一个接收者能够接收到指定的Resource Type相关的消息的方式来实现对资源的独占式写，不需要Mutex Lock，因为根本不存在竞争。

### Credits
- [Message Queue Task - Microsoft Learn](https://learn.microsoft.com/en-us/sql/integration-services/control-flow/message-queue-task)
