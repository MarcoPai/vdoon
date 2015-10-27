# 项目概况
## 一、时间点
### 10月30号之前第一版开发需求确定：
    1. 学生和导师的注册登录功能。
    2. 导师和学生可以编辑内容，完善信息。
    3. 导师列表和学生列表，导师注册完是待审核状态，学生和导师按身份不同可以查看列表。
    4. 学生字段包括：
    
    
字段名称 | 关键字 | 类型 | 描述
--------|--------|-----|---------
ID  | id | ini(11) | 
头像 |  head_img  | char(50) |   
用户名 | username  | char(20)  |
密码 | password | char(20) | 
真实姓名 | realname | char(20) |
昵称 | nickname | char(20) | 
性别 | sex | tinyint(2) | 1:男,2:女
手机号 | phone | char(11) | 
身份证 | identity_card | char(18) | 
公司 | company | varchar(100) | 
省份 | province | char(30) | 
城市 | city | char(30) | 
学校 | school | varchar(100) | 
入学年份 | entrance_year | int(11) | 
学历/学位 | degree | char(20) | 
学号 | learn_number | varchar(50) | 
专业 | major | varchar(100) | 
用户类型 | user_type | tinyint(2) | 1:学徒,2:导师
个人介绍 | introduction | text | 
用户标签 | tag_ids | char(255) | 
注册时间 | register_time | datetime | 
注册IP | register_ip | char(15) | 
注册IP归属省 | register_ip_province | char(30) | 
注册IP归属市 | register_ip_city | char(30) | 
注册来源 | register_source | tinyint(2) | 1:微信
平台ID | plat_user_id | char(100) | 
状态 | status | tinyint(2) | 1:正常,2:冻结
    

### 11月～第二版需求（视运营情况而定）：
1. PC后台
    + 包括企业添加和管理
    + 导师的审核，批复或打回
    + 学生用户管理，冻结不良学生
    + 导师自己资料的更新。

2. 动态，任务，课程的优先级待讨论。
    > 达成初步共识，任务的优先级略高。
    > 可用动态加控件的形式包含任务和课程。