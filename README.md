# GNU-Radio-UHD-
GNU Radio(UHD)整体编译流程以及库依赖
从 git 下 GNU Radio 的官方仓库，到 sudo make install 完 GNU Radio 结束，我们实现了在 python 中调用 GNU Radio 库如同普通 python 库一样的操作。但是源代码杂糅了 C++和 python 文件的编写，比较晦涩难懂，各种函数的依赖较为复杂，这里我将结合实际阅读源代码的经验出发，简明介绍 GNU Radio 库的整体编译流程。UHD 类同。
