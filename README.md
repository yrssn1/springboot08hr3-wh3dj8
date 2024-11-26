# springboot008房屋租赁系统

## 简介

本代码仅供学习参考使用

加QQ(**3055269939**)免费获取项目和论文

## 主要内容

## 数据表

将数据库概念设计的E-R图转换为关系数据库。在关系数据库中，数据关系由数据表组成，但是表的结构表现在表的字段上。

表4.1 config信息表

| 列名  | 数据类型 | 长度 | 约束         |
| ----- | -------- | ---- | ------------ |
| id    | bigint   | 20   | PRIMARY KEY  |
| name  | varchar  | 100  | DEFAULT NULL |
| value | varchar  | 100  | DEFAULT NULL |

表4.2 discussfangwuxinxi信息表

| 列名   | 数据类型 | 长度 | 约束         |
| ------ | -------- | ---- | ------------ |
| id     | bigint   | 20   | PRIMARY KEY  |
| refid  | bigint   | 20   | DEFAULT NULL |
| userid | bigint   | 20   | DEFAULT NULL |

表4.3 discusswoyaodangfangzhu信息表

| 列名   | 数据类型 | 长度 | 约束         |
| ------ | -------- | ---- | ------------ |
| id     | bigint   | 20   | PRIMARY KEY  |
| refid  | bigint   | 20   | DEFAULT NULL |
| userid | bigint   | 20   | DEFAULT NULL |

表4.4 fangwubaoxiu信息表

| 列名             | 数据类型 | 长度 | 约束         |
| ---------------- | -------- | ---- | ------------ |
| id               | bigint   | 20   | PRIMARY KEY  |
| hetongbianhao    | varchar  | 200  | DEFAULT NULL |
| fangwumingcheng  | varchar  | 200  | DEFAULT NULL |
| fangwuleixing    | varchar  | 200  | DEFAULT NULL |
| xiaoqu           | varchar  | 200  | DEFAULT NULL |
| baoxiumingcheng` | varchar  | 200  | DEFAULT NULL |
| leixing          | varchar  | 200  | DEFAULT NULL |
| baoxiuneirong    | varchar  | 200  | DEFAULT NULL |
| tupian           | varchar  | 200  | DEFAULT NULL |
| fangzhuzhanghao  | varchar  | 200  | DEFAULT NULL |
| fangzhuxingming  | varchar  | 200  | DEFAULT NULL |
| yonghuming       | varchar  | 200  | DEFAULT NULL |
| lianxidianhua    | varchar  | 200  | DEFAULT NULL |
| sfsh             | varchar  | 200  | DEFAULT NULL |

表4.5 fangwuleixing信息表

| 列名          | 数据类型 | 长度 | 约束         |
| ------------- | -------- | ---- | ------------ |
| id            | bigint   | 20   | PRIMARY KEY  |
| fangwuleixing | bigint   | 20   | DEFAULT NULL |

表4.6 fangwupingjia信息表

| 列名            | 数据类型 | 长度 | 约束         |
| --------------- | -------- | ---- | ------------ |
| hetongbianhao   | varchar  | 11   | DEFAULT NULL |
| fangwumingcheng | varchar  | 200  | DEFAULT NULL |
| fangwuleixing   | varchar  | 200  | DEFAULT NULL |
| xiaoqu          | varchar  | 200  | DEFAULT NULL |
| pingfen         | varchar  | 200  | DEFAULT NULL |
| fangzhuzhanghao | varchar  | 200  | DEFAULT NULL |
| yonghuming      | varchar  | 200  | DEFAULT NULL |
| lianxidianhua   | varchar  | 200  | DEFAULT NULL |
| sfsh            | varchar  | 200  | DEFAULT NULL |

表4.7 fangzhu信息表

| 列名            | 数据类型 | 长度 | 约束         |
| --------------- | -------- | ---- | ------------ |
| id              | bigint   | 200  | PRIMARY KEY  |
| fangzhuzhanghao | varchar  | 200  | DEFAULT NULL |
| mima            | varchar  | 200  | DEFAULT NULL |
| fangzhuxingming | varchar  | 200  | DEFAULT NULL |
| xingbie         | varchar  | 200  | DEFAULT NULL |
| touxiang        | varchar  | 200  | DEFAULT NULL |
| shouji          | varchar  | 200  | DEFAULT NULL |
| shenfenzheng    | varchar  | 200  | DEFAULT NULL |

表4.8 messages信息表

| 列名     | 数据类型 | 长度 | 约束         |
| -------- | -------- | ---- | ------------ |
| id       | bigint   | 11   | DEFAULT NULL |
| userid   | username | 200  | DEFAULT NULL |
| username | varchar  | 200  | DEFAULT NULL |

表4.9 news信息表

| 列名    | 数据类型 | 长度 | 约束         |
| ------- | -------- | ---- | ------------ |
| id      | bigint   | 20   | PRIMARY KEY  |
| title   | varchar  | 200  | DEFAULT NULL |
| picture | varchar  | 200  | DEFAULT NULL |