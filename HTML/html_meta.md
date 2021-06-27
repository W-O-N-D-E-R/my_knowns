<!-- HTML META -->

1. 定义

>meta标签提供关于 HTML 文档的元数据。它不会显示在页面上，但是对于机器是可读的。可用于浏览器（如何显示内容或重新加载页面），搜索引擎（关键词），或其他 web 服务。

2. 作用

>meta里的数据是供机器解读的，告诉机器该如何解析这个页面，还有一个用途是可以添加服务器发送到浏览器的http头部内容

3. 必要属性

>meta的必需属性是content，当然并不是说meta标签里一定要有content，而是当有http-equiv或name属性的时候，一定要有content属性对其进行说明。

4. 可选属性

>在W3school中，对于meta的可选属性说到了三个，分别是http-equiv、name和scheme。
>
>- http-equiv
>
>>http-equiv属性是添加http头部内容，对一些自定义的，或者需要额外添加的http头部内容，需要发送到浏览器中
>>
>>五秒钟后主动跳转到指定页面：&lt;meta http-equiv="Refresh" content="5;url=xxx" /&gt;
>
>- name
>
>>供浏览器进行解析，对于一些浏览器兼容性问题，name属性是最常用的，当然有个前提就是浏览器能够解析你写进去的name属性才可以，不然就是没有意义的。

- **H5标准声明**

~~~
<!DOCTYPE html>
~~~

- **标准的 lang 属性写法**

~~~
<head lang="en">
~~~

- **声明文档使用的字符编码** (必须写在第一行)

~~~
<meta charset="utf-8">
~~~

- **网页标题**

~~~
<title>标题</title>
~~~

- **优先使用 IE 最新版本和 Chrome**

~~~
<meta http-equiv=”X-UA-Compatible” content=”IE=edge,chrome=1″/>
~~~

- **页面描述**

~~~
<meta name=”description” content=”不超过150个字符”/>
~~~

- **页面关键词**

~~~
<meta name=”keywords” content=””/>
~~~

- **网页作者**

~~~
<meta name=”author” content=”name, email@gmail.com”/>
~~~

- **搜索引擎抓取**

  > 定义网页搜索引擎索引方式，content是一组使用英文逗号「,」分割的值，通常有如下几种取值：none，noindex，nofollow，all，index和follow。

~~~
<meta name=”robots” content=”index,follow”/>
~~~

- **移动设备添加 viewport**

  >width viewport 宽度(数值/device-width)
  >height viewport 高度(数值/device-height)
  >initial-scale 初始缩放比例
  >maximum-scale 最大缩放比例
  >minimum-scale 最小缩放比例
  >user-scalable 是否允许用户缩放(yes/no)

~~~
<meta name=”viewport” content=”initial-scale=1, maximum-scale=3, minimum-scale=1, user-scalable=no”>
~~~

- **添加到主屏后的标题（iOS 6 新增）**

~~~
<meta name=”apple-mobile-web-app-title” content=”标题”>
~~~

- **是否启用 WebApp 全屏模式，删除苹果默认的工具栏和菜单栏**

~~~
<meta name=”apple-mobile-web-app-capable” content=”yes”/>
~~~

- **添加智能 App 广告条 Smart App Banner（iOS 6+ Safari）**

~~~
<meta name=”apple-itunes-app” content=”app-id=myAppStoreID, affiliate-data=myAffiliateData, app-argument=myURL”>
~~~

- **设置苹果工具栏颜色**

~~~
<meta name=”apple-mobile-web-app-status-bar-style” content=”black”/>
~~~

- **启用360浏览器的极速模式(webkit)**

~~~
<meta name=”renderer” content=”webkit”>
~~~

- **避免IE使用兼容模式**

~~~
<meta http-equiv=”X-UA-Compatible” content=”IE=edge”>
~~~

- **不让百度转码**

~~~
<meta http-equiv=”Cache-Control” content=”no-siteapp” />
~~~

- **UC强制竖屏**

~~~
<meta name=”screen-orientation” content=”portrait”>
~~~

- **QQ强制竖屏**

~~~
<meta name=”x5-orientation” content=”portrait”>
~~~

- **UC强制全屏**

~~~
<meta name=”full-screen” content=”yes”>
~~~

- **QQ强制全屏**

~~~
<meta name=”x5-fullscreen” content=”true”>
~~~

- **UC应用模式**

~~~
<meta name=”browsermode” content=”application”>
~~~

- **QQ应用模式**

~~~
<meta name=”x5-page-mode” content=”app”>
~~~

- **设置页面不缓存**

~~~
<meta http-equiv=”pragma” content=”no-cache”>
<meta http-equiv=”cache-control” content=”no-cache”>
<meta http-equiv=”expires” content=”0″>
~~~

- **禁止自动翻译**

~~~
<meta name="google" value="notranslate">
~~~

