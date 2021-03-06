# Swoole Source Analysis

## 阅读顺序

- [Swoole 源码分析——内存模块之内存池](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20源码分析——内存模块之内存池.md)
- [Swoole 源码分析——内存模块之共享内存](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20源码分析——内存模块之共享内存.md)
- [Swoole 源码分析——内存模块之共享内存表](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20源码分析——内存模块之共享内存表.md)
- [Swoole 源码分析——内存模块之 swBuffer](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20源码分析——内存模块之swBuffer.md)
- [Swoole 源码分析——基础模块之 HashMap](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20源码分析——基础模块之HashMap.md)
- [Swoole 源码分析——基础模块之锁与信号 ](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90%E2%80%94%E2%80%94%E5%9F%BA%E7%A1%80%E6%A8%A1%E5%9D%97%E4%B9%8B%E9%94%81%E4%B8%8E%E4%BF%A1%E5%8F%B7.md)
- [Swoole 源码分析——Reactor 模块之 ReactorBase](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20源码分析——Reactor模块之ReactorBase.md)
- [Swoole 源码分析——Reactor 模块之 ReactorEpoll](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20源码分析——Reactor%20模块之%20ReactorEpoll.md)
- [Swoole 源码分析——Server 模块之初始化](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20源码分析——Server模块之construct.md)
- [Swoole 源码分析——Server 模块之 Start](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20源码分析——Server模块之Start.md)
- [Swoole 源码分析——Server 模块之 ReactorThread 事件循环（上）](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20源码分析——Server模块之ReactorThread事件循环.md)
- [Swoole 源码分析——Server 模块之 ReactorThread 事件循环（下）](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20源码分析——Server模块之ReactorThread事件循环（下）.md)
- [Swoole 源码分析——Server 模块之 Worker 事件循环](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20源码分析——Server模块之Worker事件循环.md)
- [Swoole 源码分析——Server 模块之 Stream 模式](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20源码分析——Server模块之Stream%20模式.md)
- [Swoole 源码分析——Server 模块之 TaskWorker 事件循环](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20源码分析——Server模块之TaskWorker事件循环.md)
- [Swoole 源码分析——Server 模块之 Timer 模块与时间轮](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20源码分析——Server模块之Timer模块.md)
- [Swoole 源码分析——Server 模块之 Signal 信号处理](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20源码分析——Server模块之Signal信号处理.md)
- [Swoole 源码分析——基础模块之 Queue 队列](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20源码分析——基础模块之%20Queue%20队列.md)
- [Swoole 源码分析——基础模块之 Heap 堆](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20源码分析——基础模块之%20Heap%20堆.md)
- [Swoole 源码分析——基础模块之 Channel 队列](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20源码分析——基础模块之%20Channel.md)
- [Swoole 源码分析——基础模块之 Pipe 管道](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20源码分析——基础模块之%20Pipe%20管道.md)
- [Swoole 源码分析——Server模块之OpenSSL(上)](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90%E2%80%94%E2%80%94Server%E6%A8%A1%E5%9D%97%E4%B9%8BOpenSSL(%E4%B8%8A).md)
- [Swoole 源码分析——Server模块之OpenSSL(下)](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90%E2%80%94%E2%80%94Server%E6%A8%A1%E5%9D%97%E4%B9%8BOpenSSL(%E4%B8%8B).md)
- [Swoole 源码分析——Async 异步事件系统 Swoole_Event](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90%E2%80%94%E2%80%94Async%20%E5%BC%82%E6%AD%A5%E4%BA%8B%E4%BB%B6%E7%B3%BB%E7%BB%9Fswoole_event.md)
- [Swoole 源码分析——进程管理 Swoole_Process](https://github.com/LeoYang90/swoole-source-analysis/blob/master/Swoole%20%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90%E2%80%94%E2%80%94%E8%BF%9B%E7%A8%8B%E7%B3%BB%E7%BB%9F%20Swoole_Process.md)
