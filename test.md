### 项目命名（js，css，scss，html文件相同规则）

全部采用小写方式， 以下划线分隔。
例：my_project_name



### 目录命名

参照项目命名规则；
有复数结构时，要采用复数命名法。
例：scripts, styles, images, data_models



### Div+CSS代码命名规范

#### （一）窗体

头：header
内容：content/container
尾：footer
导航：nav
侧栏：sidebar
栏目：column
页面外围控制整体布局宽度：wrapper
左右中：left right center
登录条：loginbar
标志：logo
广告：banner
页面主体：main
热点：hot
新闻：news　　
下载：download　　
子导航：subnav　　
菜单：menu
子菜单：submenu　　
搜索：search　　
友情链接：friendlink　　
页脚：footer
版权：copyright　　
滚动：scroll　　
内容：content　　
标签页：tab
文章列表：list　　
提示信息：msg　　
小技巧：tips　　
栏目标题：title
加入：joinus　　
指南：guild　　
服务：service　　
注册：regsiter
状态：status　　
投票：vote　　
合作伙伴：partner

#### (二) css  id的命名:

##### (1)页面结构

容器: container
页头：header
内容：content/container
页面主体：main
页尾：footer
导航：nav
侧栏：sidebar
栏目：column
页面外围控制整体布局宽度：wrapper
左右中：left right center

##### (2)导航

导航：nav　　
主导航：mainnav　　
子导航：subnav 　　
顶导航：topnav　　
边导航：sidebar　　
左导航：leftsidebar 　　
右导航：rightsidebar　　
菜单：menu　　
子菜单：submenu 　　
标题: title　　
摘要: summary


(3)功能　　
标志：logo　　
广告：banner　　
登陆：login　　
登录条：loginbar 　　
注册：regsiter　　
搜索：search　　
功能区：shop 　　
标题：title　　
加入：joinus 　
状态：status　　
按钮：btn 　　
滚动：scroll　　
标签页：tab　　
文章列表：list　　
提示信息：msg 　　
当前的: current　　
小技巧：tips　　
图标: icon　　
注释：note 　　
指南：guild　
服务：service　　
热点：hot　　
新闻：news 　　
下载：download　　
投票：vote　　
合作伙伴：partner 　　
友情链接：link　　
版权：copyright


（三 ) class的命名:
 (1)颜色:使用颜色的名称或者16进制代码,如　　


.red { color: red; } 　　.f60 { color: #f60; } 　


　.ff8600 { color: #ff8600; }


(2)字体大小,直接使用’font+字体大小’作为名


称,如　　


.font12px { font-size: 12px; } 　　.font9pt 


{font-size: 9pt; }


(3)对齐样式,使用对齐目标的英文名称,如　　


.left { float:left; } 　　.bottom { float:bottom; }


(4)标题栏样式,使用’类别+功能’的方式命名,如


　


.barnews { } 　　.barproduct { }


注意事项:: 　　


1.一律小写; 　　


2.尽量用英文; 　　


3.不加中杠和下划线; 　　


4.尽量不缩写，除非一看就明白的单词. 　
　主要的 master.css　　模块 module.css　　基


本共用 base.css 　　布局，版面layout.css　　


主题 themes.css　　专栏 columns.css 　　文字 


font.css　　表单 forms.css　　补丁 mend.css


　　打印print.css



（四）css书写顺序
CSS书写顺序
1.位置属性(position, top, right, z-index,display, float等)
2.大小(width, height, padding, margin)
3.文字系列(font, line-height, letter-spacing,color- text-align等)　　
4.背景(background, border等)
5.其他(animation, transition等)
