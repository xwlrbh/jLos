# jLos
简单易用的浏览器本地存储

欢迎访问 [jLos](http://jlos.catfish-cms.com)

## 使用方法: ##
**1, 引入jLos的javaScript文件**

    <script src="jLos.js"></script>

**2, 开启jLos**

    var jlos = jLos.open();

**3, 存入数据到浏览器本地**

*键名key可以任意取值*

    jlos.set('key', '存入的数据');

**4, 获取本地数据**

*键名需要和set中的相同*

    jlos.get('key');

**5, 删除本地数据**

*键名需要和set中的相同*

    jlos.remove('key');

----------

获取更多高级用法请访问 [Catfish CMS](http://www.catfish-cms.com) 官方网站或者访问 [jLos](http://jlos.catfish-cms.com)
