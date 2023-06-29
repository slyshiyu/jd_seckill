# Jd_Seckill

##### 非常感谢原作者 https://github.com/zhou-xiaojun/jd_mask 提供的代码
##### 也非常感谢 https://github.com/wlwwu/jd_maotai 进行的优化

## 主要功能

- 登陆京东商城（[www.jd.com](http://www.jd.com/)）
  - cookies登录 (需要自己手动获取)
- 预约茅台
  - 定时自动预约
- 秒杀预约后等待抢购
  - 定时开始自动抢购

## 运行环境

- [Python 3](https://www.python.org/)

## 第三方库

- 需要使用到的库已经放在requirements.txt，使用pip安装的可以使用指令  
`pip install -r requirements.txt`

## 使用教程  
#### 1. 网页扫码登录
#### 2. 填写config.ini配置信息 
(1)eid和fp用浏览器打开京东，并登陆，随意选择一个商品进入提交界面，将get_eid_fp.html文件拖到当前浏览器，即可看到想要的eid和fp值

(2)cookies_string，sku_id，DEFAULT_USER_AGENT(和cookie获取同一个地方就会看到.直接复制进去就可以了) 
>cookie可以通过log.gif的请求获取，sku_id在商品详情页从url即可复制，DEFAULT_USER_AGENT可以不用改

(3)配置一下时间
 
以上都是必填的.

#### 3.运行main.py 
根据提示选择相应功能即可
