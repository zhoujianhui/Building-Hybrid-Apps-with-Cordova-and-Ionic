##依赖的第三方包
我们按照如下分类组织：
- 主流框架或者库
- 主流框架或者库的扩展插件
- 针对具体领域的库
- Miscellaneous

我们的引入规则：
- 需要同时引入开发版js(\*.js)和发布版js(\*.min.js);
如果第三方库没有按照此规则的，请主动改名再引入
- 引入后请按规则写在README.md中：名称,官网首页,版本号,简介

###主流框架或者库
- [jquery](http://jquery.com/) : v2.1.4
- [Ionic](http://ionicframework.com/) : v1.1.0 其打包了：
    - [angularjs](https://angularjs.org/) : v1.4.3 含angular-animate.js,angular-sanitize.js
    - [angular ui-router](https://github.com/angular-ui/ui-router) : v0.2.13

###主流框架或者库的扩展插件
- [ngCordova](http://ngcordova.com/) : v0.1.17-alpha