# IPet_99
99爱宠项目,微信web前端开发以及后台采用ThinkPHP框架的后台接口
================================================
###前端项目结构:
>- 使用frozen UI webapp框架快速搭建前端框架
>- index_store_list.html 商家list页面索引
>- index_store_detail.html 商家详情页面索引
>- index_jiyang.html 商家寄养页面索引
>- location_map.html 高德地图JSAPI获取经纬度等信息页面索引

===============================================
### 后台项目结构:
>- index.php应用入口
>- App     应用目录
>- -Conf   配置目录
>- --config.php    配置文件
>- -Lib    应用库
>- --Action 控制器
>- ---Api  后台接口分组
>- ---Core 核心逻辑处理
>- ---Weixin 微信组
>- ...
>- -Tpl    模板目录
>- --Weixin 微信模板
>- ---Index    Index控制器模板
>- ---Services Services控制器模板
>- ----getServiceInfo.html Services控制器的getServiceInfo方法的视图文件
>- ----Index.html Services控制器的Index方法的视图文件
