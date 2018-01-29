title: 图片命名
---

## 命名顺序

图片命名建议以以下顺序命名：

**图片业务（可选） +（mod_）图片功能类别（必选）+ 图片模块名称（可选） + 图片精度（可选）**

* 图片业务：
	- sw_：视睿
	- mx_：maxhub
	- wx_：微信
	- ...


* 图片功能类别：

	- mod_：是否公共，可选
	- icon：模块类固化的图标
	- logo：LOGO类
	- spr：单页面各种元素合并集合
	- btn：按钮
	- bg：可平铺或者大背景
	- ...

	
* 图片模块名称：

	- goodslist：商品列表 
	- goodsinfo：商品信息
	- useravatar：用户头像
	- ...
	
	
* 图片精度：

	- 普清：@1x
	- Retina：@2x | @3x
	- ...

	
如下面例子：

	公共模块：
	wx_mod_btn_goodlist@2x.png
	wx_mod_btn_goodlist.png
	mod_btn_goodlist.png 
	
	非公共模块：
	wx_btn_goodlist@2x.png
	wx_btn_goodlist.png
	btn_goodlist.png


处理高清图片的时候，命名应该加上图片相应的精度说明

	推荐：
	sw_logo@1x.png
	sw_logo@2x.png

	不推荐：
	sw_logo.png
	sw_logo_retina.png
