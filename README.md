UPDATE
===
X1.5.0
·增加插件机制
·增加编辑器附件上传功能
·核心升级至thinkphp 3.2.3，必须开启php_pdo_mysql扩展
·优化系统权限管理，增加auth+rbac混合认证模式
·增加文件存储扩展支持，默认支持本地和七牛云存储
·增加手机模板支持
·增加手机模板侦测后台开启关闭功能，默认关闭手机模板侦测
·增加MUI手机开发框架
·增加评论时间间隔设置
·增加视频插入
·增加去除模板文件里面的html空格与换行
·增加后台管理员列表分页
·增加文章页上一篇、下一篇功能
·优化菜单管理方式，采用增加文件方式菜单管理，方便程序升级
·优化导航鼠标划过下拉菜单
·优化管理员信息编辑,增加字段过滤
·优化非后台入口登录跳转到首页
·修复simplebootx搜索链接错误
·修复ucenter各种问题
·修复后台邮件发件人无法设置
·修复入口文件SITE_PATH常量部分服务器异常
·修复sae头像裁剪
·修复分类编辑时层级出错
·修复备份还原数据为空
·统一所有模块模板路径分割符为/
·删除thinkphp Vendor目录第三方类库
·移除SendMail方法
·替换scandir方法为sp_scan_dir
·统一SAE判断方法

·统一ajaxReturn为thinkphp 3.2.*以后用法，如果一直用thinkphp  3.0以前的用法，扩展时注意用sp_ajax_return()做一下升级

注：后台模板分割符已经统一为/，原来的类似Admin/Main.index.html文件已经改为Admin/Main/index.html请后台开发时注意
ThinkCMF全体贡献者祝大家2015年大吉大利，开心幸福！《给你一个吻》

===
X1.3.0
·统一Action为Controller
·增加文章搜索功能
·增加前台编辑器
·增加模板常量__STATICS__
·增加最后评论时间写入
·修复leuu bug 
·CommonModel _before_write 数据过滤bug
·后台评论管理,默认所有评论
·文章分类path更新优化
·simplebootx模板文章页css样式优化
·修复分页类bug
·后台文章编辑所有文章链接错误
·修复bug#4验证码不显示
·优化bug#3页面使用LEUU函数后每个页面都查询
·优化公共模型的调用方法，以兼容php5.3.0-5.3.2
·修复sp_sql_posts_bycatid和sp_sql_posts_paged_bycatid两个方法where语句问题
·修复bluesky主题分页样式问题
·修复文章推荐，置顶bug
===
X1.2.0
·url美化
·特殊用户名过滤
·增加推荐，置顶功能
·幻灯片隐藏显示功能
·广告隐藏显示功能
·友情链接隐藏显示功能
·评论计数
===
X1.1.0
全新的ThinkPHP 3.2.2架构，使用php命名空间，让开发快起来吧！

·统一Member应用为User,合并前台会员和后台管理员
·完善用户中心，会员登录注册
·增加编辑头像，绑定账号，我的评论，我的收藏
·增加文章点赞，收藏，查看功能，可与其它应用共用
·增强文章评论功能，方便多应用共用
·优化留言功能，增强安全性
·优化前台模板，增加多个实用组件，方便以后复用
·增加后台风格切换功能；
·增加后台风格bluesky
·优化后台菜单使用方式
·优化数据库中一些不规范字段
·增加前台标签库TagLibHome，统一include标签为tc_include
===
X1.0.0
全新的ThinkPHP 3.2.2架构，使用php命名空间，让开发快起来吧！

·统一前后台UI框架为simpleboot(bootstrap 2.3.2 ThinkCMF优化版)
·集成Ucenter
·增加文章评论功能
·增加留言功能
·全面支持SAE云平台
·增加文章内分页功能
·升级后台编辑器到Ueditor最新版本
·优化后台ajax提交，未登陆时自动退出
·优化后台所有文章按发布时间递减排序
·修复后台密码会偶然不对的错误
·修复SAE，linux下类库加载失败
·修复ueditor chrome模板功能bug
·修复文件上传bug
===
X1.0.0 alpha2
修复SAE，linux下类库加载失败
修复ueditor chrome模板功能bug
修复文件上传bug


X1.0.0 alpha
全新的ThinkPHP 3.2.2架构，使用php命名空间，让开发快起来吧！
·集成Ucenter
·增加文章评论功能
·增加留言功能
·全面支持SAE云平台
·增加文章内分页功能
·升级后台编辑器到Ueditor最新版本
·优化后台ajax提交，未登陆时自动退出
·优化后台所有文章按发布时间递减排序
·修复后台密码会偶然不对的错误


INSTALL
===
安装请执行http://yourdomain/install/index.php
安装完成后请删除或改名install/index.php

README
===
ThinkCMF是一款基于PHP+MYSQL开发的中文内容管理框架。ThinkCMF提出灵活的应用机制，框架自身提供基础的管理功能，而开发者可以根据自身的需求以应用的形式进行扩展。每个应用都能独立的完成自己的任务，也可通过系统调用其他应用进行协同工作。在这种运行机制下，开发商场应用的用户无需关心开发SNS应用时如何工作的，但他们之间又可通过系统本身进行协调，大大的降低了开发成本和沟通成本。
官网:http://www.thinkcmf.com
文档:http://www.thinkcmf.com/index.php?m=document

ThinkCMF 免责声明
  1、利用 ThinkCMF 构建的网站的任何信息内容以及导致的任何版权纠纷和法律争议及后果，ThinkCMF 官方不承担任何责任。
  2、您一旦安装使用ThinkCMF，即被视为完全理解并接受本协议的各项条款，在享有上述条款授予的权力的同时，受到相关的约束和限制。
 
ThinkCMF 使用建议
  1、请在您的网站首页加上ThinkCMF相关链接，O(∩_∩)O~ ！

捐赠ThinkCMF
  http://www.thinkcmf.com/donate/index.html
  您的每一份帮助都将支持ThinkCMF做的更好，走的更远！
  
  
ThinkCMF 正在为你开放更多....
# se
