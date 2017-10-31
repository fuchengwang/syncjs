# syncjs
write javascript by a sync process

大致思路： 把所有模块分别包装到异步函数中， 这样既可以使用await模拟阻塞， 也可以用Promise.then()去处理异步操作。 

这种实现虽是伪同步， 但对开发人员来说是使用同步的思想去编程， 更符合人的思维习惯。

开发时间： 暂定

