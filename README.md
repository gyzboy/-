一些自己能使用的开源项目记录：  


#### 一、插件化
1. Android-Plugin-Framework  比较普遍的插件化逻辑，读取资源文件，代理插件activity  
   https://github.com/limpoxe/Android-Plugin-Framework
1. AndroidDynamicLoader 使用Fragment最为UI容器，插件内的Fragment通过配置文件进行映射，访问时通过uri访问
   https://github.com/mmin18/AndroidDynamicLoader
1. android-pluginmgr   
   https://github.com/houkx/android-pluginmgr  
   调用android系统调用插件的activity，作者思路很赞。
1. DroidPlugin  360大厂的  
   https://github.com/Qihoo360/DroidPlugin
1. ACDD   阿里的插件化，手淘中使用  
   https://github.com/bunnyblue/ACDD
1. Android-Skin-Loader 插件化原理实现的换肤  
   https://github.com/fengjundev/Android-Skin-Loader

#### 二、漏洞、性能相关
1. qark  Quick Android Review Kit 一款查看android应用漏洞的工具，很强大  
   https://github.com/linkedin/qark
1. leakcanary   检测内存泄露问题
   https://github.com/square/leakcanary  
1. stetho  Fackbook的一款开源性能检测工具，可在chrome浏览器直接查看应用状态，网络访问情况等
   https://github.com/facebook/stetho
   打开chrome://inspect 如果遇到白屏，请翻墙。。。	
1. network-connection-class   同样facebook出品的网络质量检测工具  
   https://github.com/facebook/network-connection-class
1. FlatBuffs   Google出品的一个序列化库，对于JSON解析慢的问题有了较大提升  
   二进制形式缓存，无需初始化解析器  
   无需分配比自身缓冲区更大的内存  
   这是一个例子  https://github.com/frogermcs/FlatBuffs


#### 三、MVVM开发  最近在android上很火，Model-view-viewModel  
1. MasteringAndroidDataBinding  
   https://github.com/LyndonChin/MasteringAndroidDataBinding
1. MVVM_Hacker_News  
   https://github.com/hitherejoe/MVVM_Hacker_News

#### 四、构建工具
1. buck  Fackbook的一款开源构建工具，速度极快  
   https://github.com/facebook/buck
	
#### 五、React  
1. ZhiHuDaily-React-Native  
   https://github.com/race604/ZhiHuDaily-React-Native
1. JianDan-React-Native  
   https://github.com/w4lle/JianDan-React-Native

#### 六、热加载  
1. AndFix   阿里出品的可以在线修复BUG工具  
   https://github.com/alibaba/AndFix
1. Xposed   许多热加载使用的框架基础，通过Hook的方法实现热加载  
   https://github.com/rovo89/Xposed
1. dexposed   阿里出品的基于Xposed改造的可用于热加载的框架，可用于修复在线BUG，但有的机型不支持  
   https://github.com/alibaba/dexposed
1. XLog   基于Dexposed的一个Logging工具  
   https://github.com/promeG/XLog
1. Hotpatch-Sample   使用dexposed热补丁例子  
   https://github.com/fengcunhan/Hotpatch-Sample

#### 七、系统状态收集   
1. collectd  
   https://github.com/collectd/collectd

#### 八、资源混淆  
1. AndResGuard   微信的资源混淆方案，思路是替换打包好的apk文件中的resources.arsc和资源文件，然后通过7zip压缩达到混淆和减小安装包体积的目的  
   https://github.com/shwenzhang/AndResGuard

#### 九、A/B测试
1. sixpack-java  一个开源的A/B测试框架  
   https://github.com/seatgeek/sixpack-java  
   使用前需要安装sixpack的service  
   https://github.com/seatgeek/sixpack#getting-started
