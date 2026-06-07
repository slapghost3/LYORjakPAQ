# 图书管理系统 python553

## 项目概述

图书管理系统是基于 Flask 框架开发的一个简易系统，用于实现图书的增删改查等基本管理功能。项目使用 Python 作为主要开发语言，前端界面基于 layui 框架，数据存储采用 sqlite 数据库。

## 技术栈

- 后端：Python 3.7
- Web 框架：Flask
- 数据库：Sqlite
- 依赖管理：Sqlalchemy 1.4

## 功能模块

- 用户认证
- 图书信息管理
- 图书借阅管理
- 系统设置

## 系统角色

- 系统管理员
- 普通用户

## 运行环境

- Python 3.7
- Flask
- Sqlite
- Layui

## 部署步骤

1. 确保Python 3.7环境安装完毕。
2. 安装项目依赖：
 ```bash
 pip install -r requirements.txt
 ```
3. 初始化数据库结构：
 ```bash
 python manage.py db init
 ```
4. 运行数据库迁移：
 ```bash
 python manage.py db migrate
 ```
5. 应用数据库迁移：
 ```bash
 python manage.py db upgrade
 ```
6. 运行应用：
 ```bash
 python manage.py runserver
 ```

## 目录结构

```
project/
│
├── app/
│ ├── __init__.py
│ ├── models.py
│ ├── views.py
│ ├── templates/
│ └── static/
│
├── config.py
├── manage.py
└── requirements.txt
```

## 核心亮点

- 轻量级技术栈，易于维护与二次开发。
- 灵活的角色权限设置，满足不同用户的需求。

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img12.360buyimg.com/ddimg/jfs/t1/242238/16/29313/16374/68d4e244F2fdc40e8/ed863f213ff1bfb7.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/337442/18/14702/24033/68d4e244F03d24507/292caa0f17ad95fb.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/334127/12/17104/28471/68d4e245Fe8e2a19d/92551a016af93ffe.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/162640/10/46958/16338/68d4e245Fecdb006e/be1c771a6bb1f32e.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/340538/34/14737/3552/68d4e245Fc5488959/0fa60c0f968a87d3.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/342551/27/7171/54952/68d4e245F919901a1/393ed35b30a03b79.jpg)
