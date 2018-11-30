# Anypoint studio 安装及第一个Mule Project



## 1.安装



**Software required for Mulesoft Development**

- Anypoint Studio (官网下载)
- JDK (8以上)
- Postman



## Software Requirements

| Software                                                     | Version                                                      |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| Java Environments                                            | Oracle JDK 1.8.0This version of Studio is not compatible with Java 9 or Java 10. If you are having issues installing Studio, follow [this guide](https://docs.mulesoft.com/studio/7.2/faq-jdk-requirement) to reconfigure your Java installation. |
| Operating Systems                                            | MacOS 10.12.0 Windows (32- and 64-bit) Windows 7, Windows 8, Windows 10 RHEL 7.0 Ubuntu 15.04 or later |
| Suggested Web Browsers by Platform. *Studio will always use the OS default web browser* | Windows: Microsoft Edge 25.0  Internet Explorer 11 Linux Mozilla Firefox 51.0.1  OS X Safari 10.1 |
| Maven                                                        | Studio comes with Maven 3.3.9 bundled, but you can externally use the versions: 3.3.3 or your own 3.3.9 |

 

##2.第一个Mule Project



**创建新项目**

1. 单击File，选择New>Mule Project

2. 打开新的Mule项目向导，输入我们第一个项目的名称：`My First Project`，然后单击Finish。 

![image-20181112014342626](/Users/maria/Documents/note/pictures/mule project name.png)



3. 打开一个新的空白项目,下面是用于快速构建Mule项目的各种视图： 
   ![](/Users/maria/Documents/note/pictures/画布.png)



4.开始设计我们的项目，从面板中拖拽一个HTTP的连接器放到画布上。 
注意：Studio会自动用流包装连接器,从而节约手动创建流的步骤。 

![](/Users/maria/Documents/note/pictures/tuodong.png)



## 3.在进行flow的详细设计之前需要熟悉的相关知识

1.MEL(Mule Expression Language)语言



2.RAML语法

RAML的全称是RESTful API Modeling Language，这是一种用来描述基于Restful架构的API（设计API）的语言。它的语法规范是基于YAML的新规范，因此机器与人类都能够轻易地理解其中的内容。

3.WSDL

(网络服务描述语言,Web Services Description Language)是一门基于 XML 的语言,用于描述 Web Services 以及如何对它们进行访问，它 就是这样一个基于 XML 的语言，用于描述 web service 及其函数、参数和返回值。因为是基于 XML 的，所以 WSDL 既是机器可阅读的，又是人可阅读的。