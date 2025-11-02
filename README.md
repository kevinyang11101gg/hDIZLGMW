# 前言

欢迎来到基于SSM的在线学习平台Vue版！本项目是一款致力于提供便捷、高效在线学习体验的Web应用程序。我们采用当前流行的技术栈，结合Vue.js前端框架与SSM（Spring、SpringMVC、MyBatis）后端架构，构建出这款易用、功能丰富的在线学习平台。

# 内容介绍

基于SSM的在线学习平台Vue版主要分为以下几个模块：课程展示、课程详情、在线播放、用户中心等。用户可以在平台上浏览到丰富的课程资源，查看课程详情，并进行在线学习。同时，用户中心提供了个人学习进度、收藏课程等功能，帮助用户更好地管理学习内容。此外，我们还为教师用户提供了一套简便的课程发布和管理系统。

# 技术介绍

- 语言：Java
- 使用框架：Spring、SpringMVC、MyBatis
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

# 核心代码

以下为一段项目中与课程相关的核心代码，用于查询课程列表：

```java
// CourseMapper.xml
<select id="selectCourseList" resultType="Course">
    SELECT * FROM course
    WHERE status = 1
    ORDER BY create_time DESC
</select>

// CourseService.java
public List<Course> selectCourseList() {
    return courseMapper.selectCourseList();
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

![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/286864/21/17367/174411/68b17a53F871aecec/8974e1efec7cd3be.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/293275/8/23317/46449/68b17a31F3202536f/0379245ce4f27710.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/327159/3/13015/136050/68b17a31Fe4a85817/ad54e415c7b62609.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/291397/14/26195/25649/68b17a31F48b92dd2/ef1dd60d56bdf153.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/337477/34/3504/29131/68b17a31F32830ed4/2841c73613e9b307.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/324406/4/12709/25610/68b17a32F43991ecd/0562548b85d43d13.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/302492/7/27057/25829/68b17a32Fba9988f0/6f0a4bac198ff846.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/326699/9/12714/20868/68b17a32Fecc26d7f/7ae8831d2289eb81.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/287513/23/17805/26450/68b17a33Fa8dc3b9c/7970f24d3bd91a99.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/334774/36/5955/27061/68b17a33F61e5b2dd/1dc46f4a4056e608.jpg)

