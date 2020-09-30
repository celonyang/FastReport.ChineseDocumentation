# 1. 简介

## 什么事FastReport?

FastReport提供了一个针对 .NET Core 2.x/.Net Framework 4.x平台的报表生成工具。可以宰MVC、 Web API应用中使用FastReport。

[![Image of FastReport](images/FastReport-screenshot2-small.png)](images/FastReport-screenshot2.png)

## 特性

FastReport是使用C#开发，兼容.NET Standard 2.0及以上。可扩展的FastReport体系结构，允许创建自己的对象、过滤数据导出、数据库引擎和向导。

[![Image of FastReport](images/FastReport-screenshot1-small.png)](images/FastReport-screenshot1.png)

### 报告对象

- FastReport is a band-oriented report generator. There are 13 types of bands available: Report Title, Report Summary, Page Header, Page Footer, Column Header, Column Footer, Data Header, Data, Data Footer, Group Header, Group Footer, Child and Overlay. In addition, sub-reports are fully supported. 

- A wide range of band types allows creating any kind of report: list, master-detail, group, multi-column, master-detail-detail and many more.

- Wide range of available report objects : text, picture, line, shape, barcode, matrix, table, checkbox.

- Reports can consist of several design pages, which allows reports to contain a cover, the data and a back cover, all in one file.

- The Table object allows building a tabular report with variable number of rows and/or columns, just like in MS Excel. Aggregate functions are also available.

- Powerful, fully configurable Matrix object that can be used to print pivot tables.

- Report inheritance. For creating many reports with common elements such as titles, logos or footers you can place all the common elements in a base report and inherit all other reports from this base.

### Data Sources

- You can get data from XML, CSV, Json, MS SQL, MySql, Oracle, Postgres, MongoDB, Couchbase, RavenDB, SQLite.

- FastReport has ability to get data from business objects of IEnumerable type. 

- Report can contain data sources (tables, queries, DB connections). 

- Thus you can not only use application-defined datasets but also connect to any database and use tables and queries directly within the report.

### Internal Scripting

FastReport has a built-in script engine that supports two .NET languages, C# and VB.NET. You can use all of the .NET power in your reports to perform complex data handling and much more.

## Working with report templates

You can make a report template in several ways:

- Creating report from code.

- Developing report template as XML file.

- Using the FastReport Online Designer.

- Using the FastReport Designer Community Edition (freeware). It can be downloaded from [Fast Report releases page](https://github.com/FastReports/FastReport/releases).

[![Image of FastReport](images/FastReport-screenshot3-small.png)](images/FastReport-screenshot3.png)

## Exporting

FastReport Open Source [can save](Exporting.md) documents in HTML, BMP, PNG, JPEG, GIF, TIFF, EMF.

---

[Top Page](README.md) | [Fundamentals](Fundamentals.md)
