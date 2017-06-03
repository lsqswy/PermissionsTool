android6.0权限管理
========
# Android 6.0版本(Api 23)推出了很多新的特性, 大幅提升了用户体验, 同时也为程序员带来新的负担. 动态权限管理就是这样, 
* 一方面让用户更加容易的控制自己的隐私, 
* 一方面需要重新适配应用权限. 
###时代总是不断发展, 程序总是以人为本, 让我们为应用添加动态权限管理吧! 
###这里提供了一个非常不错的解决方案, 提供源码, 项目可以直接使用.

使用方式
-------------------------
##第一步 在存储库的末尾你根 build.gradle 中添加︰

<pre>
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
</pre>

##第 2 步。添加依赖项
<pre>
  	dependencies {
	        compile 'com.github.victe2010:PermissionsTool:a177571fc9'
	}

<pre>
