c++11之前，c++要使用多线程操作，必须调用操作系统提供的线程接口，如Linux下的\<pthread.h\>，Windows下的\<window.h\>，c++11提供了语言层面的多线程操作，包含在头文件\<thread\>中，解决了跨平台问题。

# 1.线程操作
## 1.1 创建线程
使用std::thread 线程名()方式创建线程：
`std::thread thread_1(线程函数，参数)`

