<p align="center"><img src="https://wyz.xyz/assets/files/2020-08-13/1597295447-873997-nxcrm.png" width="400"></p>

<p align="center">
<a href="http://nx.tt"><img src="https://img.shields.io/badge/version-1.1.0-green" alt="Build Status"></a>
<a href="http://nx.tt"><img src="https://img.shields.io/badge/laravel-7.0-%23ef3b2d" alt="Total Downloads"></a>
<a href="http://www.dcatadmin.com/"><img src="https://img.shields.io/badge/dcatadmin-1.6.7-%234c5ec2" alt="Latest Stable Version"></a>
<a href="http://nx.tt"><img src="https://img.shields.io/badge/MYSQL-8.0-%2300758f" alt="License"></a>
</p>

## 关于 Nxcrm
 ---

Nxcrm 是宁夏南相开发的客户管理系统，包含了线索，商机，合同，收款，客户，附件，联系人，跟进动态等功能。囊括可客户管理所需的大多数功能。后期版本我们将增加小程序功能。敬请期待。  
  
    
##### DEMO：
https://crm.demo.nx.tt/admin
用户名/密码: admin


## 白色主题
 ---
 ![](https://wyz.xyz/assets/files/2020-08-13/1597299703-929541-15.jpeg)
![](https://wyz.xyz/assets/files/2020-08-13/1597299702-1812-1.jpeg)
![](https://wyz.xyz/assets/files/2020-08-13/1597299702-275937-3.jpeg)
![](https://wyz.xyz/assets/files/2020-08-13/1597299702-547261-5.jpeg)
![](https://wyz.xyz/assets/files/2020-08-13/1597299702-956460-8.jpeg)
![](https://wyz.xyz/assets/files/2020-08-13/1597299703-90334-9.jpeg)
![](https://wyz.xyz/assets/files/2020-08-13/1597299703-366323-11.jpeg)
![](https://wyz.xyz/assets/files/2020-08-13/1597299703-765415-14.jpeg)

## 深色主题
 ---
 ![](https://wyz.xyz/assets/files/2020-08-13/1597299704-84760-16.jpeg)
![](https://wyz.xyz/assets/files/2020-08-13/1597299703-498686-12.jpeg)
![](https://wyz.xyz/assets/files/2020-08-13/1597299702-144606-2.jpeg)
![](https://wyz.xyz/assets/files/2020-08-13/1597299702-405472-4.jpeg)
![](https://wyz.xyz/assets/files/2020-08-13/1597299702-686011-6.jpeg)
![](https://wyz.xyz/assets/files/2020-08-13/1597299702-820414-7.jpeg)
![](https://wyz.xyz/assets/files/2020-08-13/1597299703-227817-10.jpeg)
![](https://wyz.xyz/assets/files/2020-08-13/1597299703-630113-13.jpeg)


## 功能特性
 ---
- [x] 线索
- [x] 商机
- [x] 客户
- [x] 合同
- [x] 联系人
- [x] 跟进
- [x] 收款
- [x] 附件
- [x] 合同电子档备份
- [x] 主题切换
- [x] 数据统计
- [ ] 小程序版本
- [ ] 对接宝塔API
- [ ] 对接微擎客户数据
  

## 特别感谢
 ---
+ [Dact Admin](http://www.dcatadmin.com/)
Nxcrm基于laravel开发，得益于优秀的后台框架`Dact Admin`，使得Nxcrm可以很快的上线与大家见面。感谢`Dact Admin`的作者[jqhph](https://github.com/jqhph) ，很热心的解答了我的很多问题，也很感激`Dact Admin`QQ群内大量热心的朋友的帮助和指点。  
  
  
+ [Learnku.com](https://learnku.com/laravel/)
我自己学会编程不久，本来三月份在学习前端，用到api接口，所以想连后端一起学习了。直接上手laravel，完全不知道如何下手。然后放弃。5月份从php变量开始学起，仔细看了`Summer `老师的laravel的所有课程。讲得很详细。浅显易懂。对我一个新手来说帮助很大。也让我这么一个接触php三个月的新人做出这么一个小产品成为可能。很感激。

## 环境
 ---
 - PHP >= 7.1.0
 - Laravel 7.*
 - Fileinfo PHP Extension
  
 ## 安装
 ---
#### 方法一


将网站跟目录指向在public目录，修改根目录``.env``文件中的数据库连接方式。然后运行以下命令：

```
composer update 
```
然后执行以下命令

```
php artisan admin:install
```

紧接着执行数据库迁移

```
php artisan migrate
```

启动服务后，在浏览器打开 `http://localhost/admin`，使用用户名 `admin` 和密码 `admin`登陆。


#### 方法二


将网站跟目录指向在public目录，修改根目录``.env``文件中的数据库连接方式。

将根目录的```vendor.zip```解压在当前目录。解压完了以后，项目根目录会多了一个```vendor```文件夹

删除掉```vendor.zip```，没用了。

然后在数据库中导入根目录的 ``laravelcrm.sql``文件。此文件附带一些演示数据。

在浏览器打开 `http://localhost/admin`，使用用户名 `admin` 和密码 `admin`登陆。

## 鸣谢
 ---
`Nxcrm` 基于以下组件:

+ [Laravel](https://laravel.com/)
+ [Dact Admin](http://www.dcatadmin.com/)
+ [Laravel Admin](https://www.laravel-admin.org/)
+ [AdminLTE3](https://github.com/ColorlibHQ/AdminLTE)
+ [bootstrap4](https://getbootstrap.com/)
+ [jQuery3](https://jquery.com/)
+ [Eonasdan Datetimepicker](https://github.com/Eonasdan/bootstrap-datetimepicker/)
+ [font-awesome](http://fontawesome.io)
+ [jquery-form](https://github.com/jquery-form/form)
+ [moment](http://momentjs.com/)
+ [webuploader](http://fex.baidu.com/webuploader/)
+ [bootstrap-fileinput](https://github.com/kartik-v/bootstrap-fileinput)
+ [jquery-pjax](https://github.com/defunkt/jquery-pjax)
+ [Nestable](http://dbushell.github.io/Nestable/)
+ [toastr](http://codeseven.github.io/toastr/)
+ [editor-md](https://github.com/pandao/editor.md)
+ [fontawesome-iconpicker](https://github.com/itsjavi/fontawesome-iconpicker)
+ [layer弹出层](http://layer.layui.com/)
+ [waves](https://github.com/fians/Waves)
+ [bootstrap-duallistbox](https://www.virtuosoft.eu/code/bootstrap-duallistbox/)
+ [char.js](https://www.chartjs.org)
+ [nprogress](https://ricostacruz.com/nprogress/)
+ [bootstrap-validator](https://github.com/1000hz/bootstrap-validator)
+ [Google map](https://www.google.com/maps)
+ [Tencent map](http://lbs.qq.com/)


## 最后
 ---
 登录页面的两张图是我老家，我奶奶住过的院子和窑洞。很想念她。作为一个五大三粗的码农不知道如何表达。谨以我的第一个编程作品纪念。
 封面图可自行替换。
