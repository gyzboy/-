一些自己能使用的开源项目记录：



一、插件化
	1、Android-Plugin-Framework  比较普遍的插件化逻辑，读取资源文件，代理插件activity
		https://github.com/limpoxe/Android-Plugin-Framework
	2、AndroidDynamicLoader   使用Fragment最为UI容器，插件内的Fragment通过配置文件进行映射，访问时通过uri访问
		https://github.com/mmin18/AndroidDynamicLoader
	3、android-pluginmgr   
		https://github.com/houkx/android-pluginmgr
		调用android系统调用插件的activity，作者思路很赞。
	4、DroidPlugin  360大厂的
		https://github.com/Qihoo360/DroidPlugin
	5、ACDD   阿里的插件化，手淘中使用
		https://github.com/bunnyblue/ACDD
	6、Android-Skin-Loader 插件化原理实现的换肤
		https://github.com/fengjundev/Android-Skin-Loader

二、漏洞、性能检测
	1、qark     Quick Android Review Kit 一款查看android应用漏洞的工具，很强大
		https://github.com/linkedin/qark
	2、leakcanary   检测内存泄露问题
		https://github.com/square/leakcanary
	3、stetho  Fackbook的一款开源性能检测工具，可在chrome浏览器直接查看应用状态，网络访问情况等
		https://github.com/facebook/stetho
		打开chrome://inspect 如果遇到白屏，请翻墙。。。	
	4、network-connection-class   同样facebook出品的网络质量检测工具
		https://github.com/facebook/network-connection-class


三、MVVM开发  最近在android上很火，Model-view-viewModel
	1、MasteringAndroidDataBinding
		https://github.com/LyndonChin/MasteringAndroidDataBinding
	2、MVVM_Hacker_News
		https://github.com/hitherejoe/MVVM_Hacker_News

四、构建工具
    1、buck  Fackbook的一款开源构建工具，速度极快
        https://github.com/facebook/buck
	
五、React
	1、ZhiHuDaily-React-Native
		https://github.com/race604/ZhiHuDaily-React-Native
	2、JianDan-React-Native
		https://github.com/w4lle/JianDan-React-Native
六、热加载
	1、AndFix   阿里出品的可以在线修复BUG工具
		https://github.com/alibaba/AndFix
	2、Xposed   许多热加载使用的框架基础，通过Hook的方法实现热加载
		https://github.com/rovo89/Xposed
	3、dexposed   阿里出品的基于Xposed改造的可用于热加载的框架，可用于修复在线BUG，但有的机型不支持
		https://github.com/alibaba/dexposed
	4、XLog   基于Dexposed的一个Logging工具
		https://github.com/promeG/XLog
	5、Hotpatch-Sample   使用dexposed热补丁例子
		https://github.com/fengcunhan/Hotpatch-Sample
七、系统状态收集   
	1、collectd
		https://github.com/collectd/collectd
		  