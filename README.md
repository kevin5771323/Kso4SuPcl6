## 前言

自助购药小程序+SSM是一款基于Java语言和Spring、SpringMVC、MyBatis框架开发的在线购药平台。该项目旨在为用户提供便捷、快速的购药服务，通过微信小程序和前端技术实现用户与药品信息的实时交互。以下是关于本项目的详细介绍。

## 内容介绍

本项目主要包括以下功能模块：用户模块、药品模块、购物车模块、订单模块和支付模块。用户可以轻松注册、登录，浏览药品信息，将心仪的药品加入购物车，并进行在线支付。后台管理端可以对药品信息、用户订单等进行管理。

## 技术介绍

- 语言：Java
- 使用框架：Spring、Spring MVC、MyBatis、微信小程序
- 前端技术：JS、Vue、CSS3、Uniapp
- 开发工具：IDEA/Eclipse，Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12/14/16

## 核心代码

以下是一段关于药品查询的核心代码：

```java
// 通过MyBatis实现药品查询
public List<Drug> queryDrugs(String keyword) {
    DrugExample example = new DrugExample();
    Criteria criteria = example.createCriteria();
    criteria.andNameLike("%" + keyword + "%");
    return drugMapper.selectByExample(example);
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/333271/29/13038/83064/68c62803F394653ac/b76bee83f781995b.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/350423/3/2954/20693/68c627dbF09db78c2/1e7007b2ad3f8ca1.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/322789/34/10504/17590/68c627dbF9543ad4b/604a41ca254b1178.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/341891/14/2744/25800/68c627dcFc8ba1707/b8cdc21a05cede64.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/329575/32/13033/21764/68c627dcFdbe0e933/bbbea55ccacf7845.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/329529/5/12910/32079/68c627ddF516d3906/34b5263cc3384d70.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/332416/5/12993/8427/68c627ddF7faf7541/69fccabf34b94ad7.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/348636/18/3126/61070/68c627deFa03d08c7/07462771a79b9caa.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/350343/23/3085/92530/68c627deF6073f33d/63f57cadc40d7178.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/338815/29/10402/62901/68c627deFf3afdb39/3a7c0f01c7ea58b6.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
