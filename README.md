# 前言

欢迎来到基于SSM的在线订餐系统项目。本项目旨在为广大用户提供便捷、高效的在线订餐体验。通过使用Java语言、Spring、Springmvc、MyBatis框架以及前端技术，实现了一套完善的在线订餐系统。以下是对本项目的详细介绍。

# 内容介绍

基于SSM的在线订餐系统主要包括以下几个模块：用户模块、商家模块、菜品模块、订单模块和支付模块。用户可以通过注册、登录、浏览菜品、下单、支付等操作来体验在线订餐服务。商家可以发布菜品、处理订单、查看营业额等。系统后台可以进行用户、商家、菜品和订单的管理。

以下是本项目的主要功能：

1. 用户注册、登录、个人信息管理
2. 商家入驻、菜品发布、营业统计
3. 菜品分类、搜索、详情展示
4. 购物车、订单提交、支付
5. 后台管理：用户、商家、菜品、订单管理

# 技术介绍

本项目采用以下技术栈：

- 语言：Java
- 使用框架：Spring、Springmvc、MyBatis
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

# 核心代码

以下是本项目中的一段核心代码，展示了如何使用MyBatis进行数据查询：

```java
// 注解方式查询菜品
public List<Dish> queryDishListByAnnotation(String categoryId) {
    SqlSession sqlSession = sqlSessionFactory.openSession();
    try {
        DishMapper dishMapper = sqlSession.getMapper(DishMapper.class);
        return dishMapper.queryDishList(categoryId);
    } finally {
        sqlSession.close();
    }
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/324493/13/18158/137443/68c06432Fde43ba4b/3c8e106d25bab100.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/334510/9/11471/25646/68c0640aF67169fd3/f2d97b7b8ce2af10.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/333883/7/11373/90362/68c0640aF57fd9f77/3e7a30f8017fa03e.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/337934/30/8945/27311/68c0640bF556b6d19/8a13f4eaa5200384.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/338135/1/8871/138691/68c0640bFfab0ba65/2e6a5972cc6b4a92.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/332975/22/11517/46659/68c0640cF4eeb9a0e/6fe32b4336c84921.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/342425/34/1584/118252/68c0640cF0b7a9a20/6f62304df0376bff.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/338773/8/8761/48665/68c0640cFc53a195a/9beee89b91c05e31.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/344777/20/1558/77165/68c0640dF770e34bd/d64166cc12dc4119.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/323691/39/18053/89621/68c0640eF6b4d23be/7f6ce9329b48fa54.jpg)
