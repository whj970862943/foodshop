# foodshop

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

## 后台
    后台项目: 前后台分离
    测试后台接口: 使用postman
    
## 前后台交互
    ajax请求库: axios
    ajax请求函数封装: axios + promise
    接口请求函数封装: 每个后台接口

## 异步数据
    封装ajax: 
        promise+axios封装ajax请求的函数
        封装每个接口对应的请求函数(能根据接口定义ajax请求函数)
        解决ajax的跨越域问题: 配置代理, 对代理的理解

##  登陆/注册: 界面相关效果
    a. 切换登陆方式
    b. 手机号合法检查
    c. 倒计时效果
    d. 切换显示或隐藏密码
    g. 前台验证提示
    

##  登陆/注册实现
    1). 2种方式
       手机号/短信验证码登陆
       用户名/密码/图片验证码登陆
    2). 登陆的基本流程
       表单前台验证, 如果不通过, 提示
       发送ajax请求, 得到返回的结果
       根据结果的标识(code)来判断登陆请求是否成功
           1: 不成功, 显示提示
           0. 成功, 保存用户信息, 返回到上次路由
   
