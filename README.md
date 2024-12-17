## R语言数据可视化学习笔记

欢迎来到R语言数据可视化的学习笔记，本项目主要记录了我在学习使用R语言`ggplot2`包进行数据可视化时的一些思考和代码。

`ggplot2` 是 R 语言中一个用于创建高质量图形和图表的强大包。它是基于“图形语法”（Grammar of Graphics）理论构建的，提供了一种灵活且一致的方式来描述和构建各种复杂的图形。ggplot2 的核心思想是将图形分解为多个组成部分，包括数据 (data)、映射（aes）、几何对象（geom）、统计变换（stat）、刻度（scale）和主题（theme）等。通过组合这些组件，用户可以轻松地创建从简单的散点图和柱状图到复杂的分层图形和地图等多种类型的图表。目前，`ggplot2`已经形成强大的拓展生态系统，可以利用`ggplot2`的扩展，轻松创建更加复杂和个性化的图形。

笔记不会不含基础`ggplot2`绘图的相关知识，如果是初学者，建议先学习[ggplot2: Elegant Graphics for Data Analysis (3e)](https://ggplot2-book.org/)。在这里，主要主要包含ggplot2的一些高级用法，包括ggplot2内部如何工作，编写ggplot2扩展的原理和利用ggplot2进行高级绘图。

## 构建

本项目使用`renv`包进行依赖管理，可以轻松下载项目依赖。注意，本项目在Ubuntu 24.04 LTS系统构建通过，别的系统，特别是Windows下，使用`renv`包可能出错。

```R
# 在R中使用以下函数来进行依赖安装
renv::restore()
```

如果需要PDF文件，可以自己在构建时修改`_quarto.yml`文件，详细步骤请参考 [quarto-PDF](https://quarto.org/docs/output-formats/pdf-basics.html)

## 声明

**本项目中的所有代码只在Linux环境下测试过，Windows环境下可能无法运行，如有问题，请自行解决。**

**开发者不对项目的源码负责，如有问题，请在issue中提出**


## 贡献

欢迎对本项目进行贡献，包括但不限于：

1. R语言绘制的高级图形
2. 其他和`ggplot2`相关的主题

## 许可证

本项目采用GPL许可证，详情请参见LICENSE文件。



