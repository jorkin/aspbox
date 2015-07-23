<p><b><font color='red'>更新：<br>
基于MVC模式APP开发进行中，</font> <font color='blue'></font> → <a href='http://www.19www.com/download.html'>下载</a></b></p>

| **MVC结构** | **标 志** | **状 态** |
|:----------|:--------|:--------|
| 控制层       | （Action） | 已完成     |
| 数据层       | （Dao）   | 已完成     |
| 视图层       | （View）  | 已完成     |
| 模型层       | （Model） | <font color='red'>基本完成</font> |

<font color='green'>演示：</font>
[前台](http://demo.399d.com/appweb/) 　[WAP](http://demo.399d.com/appweb/?m=wap)
[后台](http://demo.399d.com/appweb/admin.asp) （账号密码均为admin）

<p>有什么留言或建议欢迎给我发送邮箱 lajox#19www.com (#替换成@)</p>


&lt;hr&gt;



<p>AspBox is an Open Source ASP FrameWork, ASP Library. Using AspBox, you can do easily to create ASP websites or projects.</p><p>AspBox是一个方便快速开发ASP框架，AspBox提供了大量实用的ASP通用过程及方法和子类，可以简化大部分的ASP操作。</p><p>官方网站：<a href='http://www.19www.com/'><a href='http://www.19www.com'>http://www.19www.com</a></a><br></br> 交流社区：<a href='#.md'>http://www.19www.com/bbs</a></p><p><h3>一、软件介绍</h3></p><p>AspBox还可以进行拓展子类对象以增强自身功能。封装严谨，层层嵌套，提高了代码重复利用多次利用。<br>可以说AspBox是一个比较成型的可应用于开发人员快速开发的ASP开发框架。<p><h3>二、声明</h3> </p>
<p><font color='#666666'>本程序借鉴了EasyAsp模式思想，重写核心代码，并做了改进以及修复了部分Bug，更易于书写和拓展核心，核心分工更加明细，且拓展了一些实用核心类，更方便调用。</font></p>
<p>您可以基于任何目的运行程序，学习程序如何运作以及修改程序满足您的需要，为了使周围的人群获益再次发行复制程序，改进程序并发布给公众等自由。</p>
<p><h3>三、使用环境</h3> </p><p>1、语言：ASP；数据库：ACCESS / MSSQL；</p><p>2、IIS 5.1 以上服务器，支持ASP环境的Windows服务器平台。 </p>
<h3><a></a>
四、使用说明<a href='#使用说明'></a>
</h3>
<p>
<strong>1、使用方法：</strong>
</p>
(1) AspBox核心的主要集中在Cls_AB.asp文件，所以只需要在页首引入该文件，如：<br>
<pre><code>&lt;!--#include file="inc/AspBox/Cls_AB.asp" --&gt;<br>
</code></pre>
(2) 配置AspBox相关参数(文件AB.Config.asp)<br>
<br>
<strong>2、AspBox核心主要包含了这么些核心：</strong><br>
<br>A处理Array数组<br>
<br>C通用函数类<br>
<br>Cookie操作类<br>
<br>Catch缓存类操作<br>
<br>Char字符处理类<br>
<br>D一般函数库<br>
<br>DB数据操作类<br>
<br>DBO数据操作对象<br>
<br>E加密模块(包含了Md5,Base64,SHA-1加密及收集了一些加密函数块)<br>
<br>Form表单处理块<br>
<br>Fso操作类操作<br>
<br>Html控件<br>
<br>Http对XMLHttp处理块<br>
<br>Error错误处理块<br>
<br>Json处理块<br>
<br>jsLib(JS脚本核心引用操作)<br>
<br>List处理各种List对象<br>
<br>Mail邮件处理块<br>
<br>PY拼音转换模块<br>
<br>Rnd随机数函数块<br>
<br>Session操作类<br>
<br>Sc脚本执行操作模块<br>
<br>Time时间操作块<br>
<br>Tpl模板类<br>
<br>Up,Upload上传处理块<br>
<br>Url处理块<br>
<br>X扩展块<br>
<br>Xml处理XML块<br>
<br>以及其他一些调用方法如aspjpeg组件操作,无惧上传类,艾恩上传类等<br>
<br>
<strong>3、AspBox在1.1版以上已支持MVC框架拓展</strong><br>
<br>使用方法：只需要在调用的代码前面加入： ab.use "mvc" 即可开启MVC模式<br>
<br>例：<br>
<br>AB.Use "Mvc"<br>
<br>Service.Use "Check"<br>
<br>AB.C.Print "当前访问的文件名：" & Service.Check.GetSelfName<br>
<br><font color='#888888'>

<p><b><font color='red'>1.1.0版以上已能支持MVC模式</font></b></p>

<p><font color='blue'>AspBox 1.3.2a 正式版发布</font>  <a href='http://code.google.com/p/aspbox/downloads/list?q=label:Featured'>下载地址</a></p>

<strong>插件更新<font color='green'>：</font></strong><br>
<li><a href='http://demo.19www.com/demo/run.html'>AspBox 代码测试工具</a>

<br><b><a href='http://code.google.com/p/aspbox-plugin'>下载更多插件</a></b>