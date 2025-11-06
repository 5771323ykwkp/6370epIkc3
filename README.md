# 前言

此项目为基于Java语言的课表管理系统，是毕业设计实战项目。本项目采用了当前流行的开发技术，包括Spring Boot框架、前端技术JS、Vue以及CSS3等，数据库使用MySQL 5.7/8.0，旨在为广大学生和教师提供一个便捷的课表管理工具。

# 内容介绍

本项目主要包括以下功能：学生信息管理、教师信息管理、课程信息管理、课程表查询等。学生、教师和课程信息管理实现了增删改查等基本操作，课程表查询可以根据学生或教师查询到对应的课表信息。系统界面简洁，操作方便，易于上手。

# 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

# 核心代码

以下为项目中的部分核心代码：

```java
// 获取课程信息列表
@GetMapping("/list")
public List<Course> list() {
    return courseService.list();
}

// 添加课程信息
@PostMapping("/add")
public Result add(@RequestBody Course course) {
    boolean flag = courseService.save(course);
    if (flag) {
        return new Result(true, "添加成功");
    } else {
        return new Result(false, "添加失败");
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

![封面图片](https://img12.360buyimg.com/ddimg/jfs/t1/309313/37/26617/180824/689edf3cF3cb2e403/af5dd2a16ef378f4.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/294102/3/7923/41435/689edf78Fad3bde79/1e9dca07dc04b1f6.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/290419/6/23037/137013/689edf78F89a42c2c/1e9d17b2a293752e.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/327613/9/4868/26771/689edf79F674b056e/19575e4485e28703.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/287746/7/20159/24955/689edf7aFea74f87a/6bdeefee212399cb.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/324023/34/4953/26180/689edf7aF510a0af4/87e6b73310026ed3.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/309302/13/26992/26591/689edf7aF42a7458a/854d52180b717f91.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/307304/35/26745/135037/689edf7bFf95c78d4/508764b617afdccb.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/311134/27/26659/50658/689edf7cF1586a249/5054c4caddb00258.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/318272/13/26101/53568/689edf7dFfa70d36e/746fe459e845e4f7.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
