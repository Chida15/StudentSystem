## 学生选课成绩管理系统

### 项目开发维护进展
```
    2020-02-28 初次竣工(后续等更)
```

### 项目简介
```
    这是一个基于Python Pyqt5实现的可视化学生选课成绩管理系统。
    用户面向：学生和老师

    主要功能模块有课程管理和成绩管理
    课程管理模块：
        学生可以进行本学期的课程查询，选课，退课，课程表查询，查询所修过的所有课程。
        教师可以开设本学期课程或者撤销开设的课程
    成绩管理模块：
        学生查看学期成绩单
        教师评定每门课程学生成绩

    项目意义：学习数据库相关知识并进行实际项目生产。(为了完成俺们的数据库期末大作业的动手实践(逃))
```

### 项目环境
```
    项目实现: python3.7 + mysql
    python相关包: Pyqt5, pymysql, numpy
     
    项目有关数据库和数据表：
    基于(数据库原理一)上课所学
    1. 使用的六个基本数据表: 学生表，教师表，院系表，课程表，开课表，选课表.
    2. 新创建的一个用户表。
    数据库表具体创建可参见 create.sql
```

### 项目目录
```

    --APP(程序运行主目录)
        main.py(从此文件运行整个项目运行)
        login.py
        register.py
    --BACK(后台数据库接口实现)
    --Course(课程管理模块)
    --Score(成绩管理模块)
    --image(程序图标存放)
```
