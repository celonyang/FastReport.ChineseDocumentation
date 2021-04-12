# 1. 简介

## 什么事FastReport?

FastReport提供了一个针对 .NET Core 2.x/.Net Framework 4.x平台的报表生成工具。可以宰MVC、 Web API应用中使用FastReport。

[![Image of FastReport](images/FastReport-screenshot2-small.png)](images/FastReport-screenshot2.png)

## 特性

FastReport是使用C#开发，兼容.NET Standard 2.0及以上。可扩展的FastReport体系结构，允许创建自己的对象、过滤数据导出、数据库引擎和向导。

[![Image of FastReport](images/FastReport-screenshot1-small.png)](images/FastReport-screenshot1.png)

### 报告对象

- FastReport是一个带幅面段的报表生成器。有13种类型的幅面段可用:报告标题，报告摘要，页眉，页脚，列眉，列脚，数据页眉，数据页脚，组眉，组页脚，子和覆盖。此外，完全支持子报告。. 

- 可创建报表类型: 清单报表,主从报表, 分组报表, 多列, 带子表的主从报表等.

- 报表可用的类型对象: 文本, 图片, 线, 形状, 条码, 矩阵, 数据表, 选择框.

- 报表可以由几个设计页面组成，这些页面允许报表包含一个封面、数据和一个封底，所有这些都在一个文件中。

- Table对象允许构建具有可变行数和/或列数的表格式报告，就像Excel一样。也可用聚合函数。

- 支持强大的，完全可配置的矩阵对象，可以用来打印数据透视表。

- 报告可以继承。为了创建许多具有共同元素(如标题、徽标或页脚)的报告，您可以将所有共同元素放在基本报告中，并从这个基本报告中继承所有其他报告。

### 数据源

- 数据源支持： XML, CSV, Json, MS SQL, MySql, Oracle, Postgres, MongoDB, Couchbase, RavenDB, SQLite.

- FastReport有从业务对象的IEnumerable类型中获取数据的能力。 

- Report可以包含数据源 (tables, queries, DB connections). 

- 因此，您不仅可以使用应用程序定义的数据集，还可以连接到任何数据库，并在报表中直接使用表和查询。

### 内部脚本

FastReport有一个内置的脚本引擎，支持两种。net语言，c#和VB.NET。您可以在报表中使用所有的. net功能来执行复杂的数据处理等。

## 报表模板

可以通过多种方式制作报表模板：

- 使用代码创建报表.

- 利用XML文件创建报表.

- 使用在线设计器创建报表.

- 使用FastReport社区版创建(freeware).社区版下载地址 [Fast Report releases page](https://github.com/FastReports/FastReport/releases).

[![Image of FastReport](images/FastReport-screenshot3-small.png)](images/FastReport-screenshot3.png)

## 导出

FastReport开源版本 [可以保存的文档类型](Exporting.md) ： HTML, BMP, PNG, JPEG, GIF, TIFF, EMF.

---

[Top Page](README.md) | [Fundamentals](Fundamentals.md)
