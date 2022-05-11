## sp18 中关于导入项目的说明

[sp18 lab2 ](https://sp18.datastructur.es/materials/lab/lab2setup/lab2setup#:~:text=Upon%20opening%20IntelliJ%2C%20click%20on%20the%20%E2%80%9Cimport%20project%E2%80%9D%20option)教程中提到使用 `import project` 按钮进行项目导入, 但是在新版 idea 中已经没有这个按钮,如果已经在一个项目里面了, 可以点击顶部菜单栏的 `File -> New -> project from exsisting source `, 即可导入.

## 关于插件的说明

新版本中原来的 `CS 61B` 插件已经拆分为 `CS 61B` 和 `java visualizer` 两个插件, 分别下载即可

>  不过个人经验是只用到了检查代码规范的功能, visualizer 初学 java 可以看一看, 不过教程里一般会提供 visualizer 的一个网页段, 做算法题可能有点用, 工程个人感觉作用不大的样子


## 关于导入 sp18 提供的库的说明

参见[Lab 2 setup](https://sp18.datastructur.es/materials/lab/lab2setup/lab2setup#:~:text=sidebar%20will%20appear.-,Getting%20Java%20Libraries,-Remember%20the%20empty), 但是还是在此强调, 导入的时候要**点到 javalib 那一层再导入**, 不要点到 library-sp18 就急忙忙地点击确定了, 附上目录结构

```
library-sp18/
└── javalib
 ├── algs4.jar
 ├── hamcrest-core-1.3.jar
 ├── jh61b.jar
 ├── junit-4.12.jar
 ├── stdlib-package.jar
 └── stdlib.jar
```

> 如果通过教程没能下载得到 library 的话可以手动下载导入, 在此将此库放在本目录下, 请手动下载并且导入, 如果不会, 参考https://www.lmstfy.icu/Baidu/?q=aWRlYSDlpoLkvZXlr7zlhaUIIGphciDljIU=
