CountDownLatch在完成一组正在其他线程中执行的操作之前，允许一个或者多个线程一直等待。不能被重用。

CountDownLatch依赖Sync，内部通过共享锁实现。