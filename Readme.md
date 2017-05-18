# Web 中文字体应用指南

## font

由于中文字体组成的特殊性导致其体积过于庞大，除了操作系统内置的字体之外，我们很难在网站上应用其他的字体。在可选性很差的前提之下，如何正确的使用中文字体呢？

首先，以下的字体声明都是很糟糕的，切忌使用：

    font-family: "宋体";

    font-family: "宋体", Arial;

    font-family: Arial, "宋体", "微软雅黑";

    font-family: Helvetica, Arial, "华文细黑", "微软雅黑";
