## 协议
网址、API 地址和静态资源地址等，统一使用 HTTPS 协议。

## CDN
#### 1. 公共库 CDN
公共库的引用请用 `cdn.liruan.cn` 域名，请到 [CDNJS](https://cdnjs.com/) 上获取公共库的最新版本。
> 如：`//cdn.liruan.cn/jquery/3.2.1/jquery.min.js`

#### 2. 项目静态资源 CDN
项目静态资源请用 `lrcdn.cn` 域名。
> 如：`//{app}.lrcdn.cn/static/styles/commons.css`

## 环境命名规范
开发环境
> 网站：`https://{app}.dev.liruan.cn`  
> API：`https://{app}-api.dev.liruan.cn`  
> CDN：`//{app}.dev.lrcdn.cn`  
> 数据库：`{app}-dev`

测试环境
> 网站：`https://{app}.test.liruan.cn`  
> API：`https://{app}-api.test.liruan.cn`  
> CDN：`//{app}.test.lrcdn.cn`  
> 数据库：`{app}-test`

预生产环境
> 网站：`https://{app}.beta.liruan.cn`  
> API：`https://{app}-api.beta.liruan.cn`  
> CDN：`//{app}.beta.lrcdn.cn`  
> 数据库：`{app}-beta`

生产环境
> 网站：`https://www.{app}.cn` 或 `https://{app}.liruan.cn`  
> API：`https://{app}-api.liruan.cn`  
> CDN：`//{app}.lrcdn.cn`  
> 数据库：`{app}`

Git 仓库项目名
> 网站：`{app}`  
> API：`{app}-api`

## 时间管理
例会
> [周一]  10:00-11:00

技术分享会
> [周二]  10:00-12:00

数据备份
> [每天]  01:00-04:00

大版本发布
> [周四]  18:30

hotfix 发布
> [随时]  严重 bug 需在 4 个小时内发布

## 规范
git 工作流
> [git flow 工作流](https://github.com/zhaotoday/product-workflow)

服务器环境
> php + nginx

开发规范
> ...

## 开发工具
切图及标注工具
> [NoMark](http://www.effectiveall.com/)

IDE
> WebStorm、PhpStorm

控制面板
> [宝塔](https://www.bt.cn/)

服务器安全软件
> [云锁](http://www.yunsuo.com.cn/)

其他服务器软件
> [swish-sftp（将 SSH/SFTP 集成入资源管理器管理文件）](http://www.swish-sftp.org/)

部署系统
> [瓦力上线部署](https://walle-web.io/)

自助 git 服务
> [gogs](https://gogs.io/)

命令行工具
> Windows 下推荐使用 [cmder](http://cmder.net/)

图标管理
> [Iconfont](http://www.iconfont.cn/)

翻墙
> [Proxy SwitchySharp](https://chrome.google.com/webstore/detail/proxy-switchysharp/dpplabbmogkhghncfbfdeeokoefdjegm)

Windows 远程桌面管理
> [Remote Desktop Organizer](http://www.softpedia.com/get/Internet/Remote-Utils/Remote-Desktop-Organizer.shtml)

抓包
> [Fiddler](http://www.telerik.com/fiddler)

Markdown 编辑器
> [typora](https://www.typora.io/#windows)、[在线 Markdown 编辑器](https://www.zybuluo.com/mdeditor)

接口调试
> [Postman](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop)

MySQL 数据库管理
> Navicat

API 协作管理
> [apizza](http://apizza.cc/)

Axure 原型工具
> [AntD Library](http://library.ant.design/)

企业邮箱
> [腾讯企业邮](https://exmail.qq.com/)

团队沟通
> [企业微信](https://work.weixin.qq.com/?from=mp_home)、[零信](https://pubu.im/)

云端 Office
> [一起写](https://yiqixie.com/)、[有道云笔记](http://note.youdao.com/)

Mock
> [Easy Mock](http://easy-mock.com/)

App 一站式解决方案
> [阿里轻舟](https://boat.alibaba.com) 

## 云服务
CDN 加速、防 DDos
> [知道创宇云安全](https://www.yunaq.com/)、[百度云加速](https://su.baidu.com/)、[快云 CDN](http://www.kuaiyun.cn/cdnindex)

DNS（宕机检测、故障时切换到备用 IP）
> [CloudXNS](https://www.cloudxns.net/)、[DNS 盾](https://www.dnsdun.com/)、[DNSLA](https://www.dns.la/) 

前端公共库 CDN
> [BootCDN](http://www.bootcdn.cn/)

SSL 证书
> [腾讯云 SSL 证书](https://www.qcloud.com/product/ssl)

团队协作、项目管理
> [Team@OSC](https://team.oschina.net/)、[iCafe@Baidu](http://cafe.baidu.com/)、[EasyPM](https://easypm.cn/)、[Teambition](https://www.teambition.com/)

短信
> [野狗](https://www.wilddog.com/product/message-overview)

云端文档、表格
> [石墨文档](https://shimo.im/)

云评测、云检测、云加速
> [mmtrix](http://www.mmtrix.com/)

后端云
> [Bmob](https://www.bmob.cn/)

Node.js 性能平台
> [阿里云 Node.js 性能平台](https://node.console.aliyun.com/)

移动推送
> [腾讯移动推送](http://xg.qq.com)

付费接口
> [极速数据](http://www.jisuapi.com)、[聚合数据](https://www.juhe.cn)、[百度 API 服务](http://apistore.baidu.com)、[iDataAPI](http://www.idataapi.cn)

## 服务商
域名
> [爱名网](https://www.22.cn/)、[易名中国](http://www.ename.com/)、[万网](https://wanwang.aliyun.com/)

云服务器
> [小鸟云](https://www.niaoyun.com/)、[腾讯云](https://www.qcloud.com/)、[景安](http://www.zzidc.com/)、[阿里云](https://www.aliyun.com/)、[美团云](https://www.mtyun.com/)、[尊云](http://www.zun.com/)、[天翼云](http://www.ctyun.cn/)、[百度云](https://cloud.baidu.com/)、[华为云](http://www.huaweicloud.com)

云存储、CDN
> [七牛云](https://www.qiniu.com/)

代码托管
> [码云](http://git.oschina.net/)、[阿里云](https://code.aliyun.com/)

企业云盘
> [360 企业云盘](https://eyun.360.cn/)

聚合支付
> [ping++](https://www.pingxx.com/)

小程序后端云服务
> [知晓云](https://cloud.minapp.com/)

第三方全域数据服务商
> [友盟+](http://www.umeng.com/)
