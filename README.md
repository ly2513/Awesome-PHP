---
title: Awesome PHP(PHP相关资料的收集汇总)
date: 2017-07-10 18:15:20
category:
tags: php
---
# Awesome PHP
一个PHP资源列表，内容包括：库、框架、模板、安全、代码分析、日志、第三方库、配置工具、Web 工具、书籍、电子书、经典博文等等

## 贡献
详细内容请查看[贡献](https://github.com/ziadoz/awesome-php/blob/master/CONTRIBUTING.md) 和 [代码管理](https://github.com/ziadoz/awesome-php/blob/master/CODE-OF-CONDUCT.md).
<!-- more -->
## 目录
- [Awesome PHP](#awesome-php)
    - [依赖管理 Dependency Management](#依赖管理-dependency-management)
    - [其他的依赖管理 Dependency Management Extras](#其他的依赖管理-dependency-management-extras)
    - [框架 Frameworks](#框架-frameworks)
    - [其他框架 Framework Extras](#其他框架-framework-extras)
    - [框架组件 Components](#框架组件-components)
    - [微型框架 Micro Frameworks](#微型框架-micro-frameworks)
    - [其他微型框架 Micro Framework Extras](#其他微型框架-micro-framework-extras)
    - [路由 Routers](#路由-routers)
    - [模板 Templating](#模板-templating)
    - [静态站点生成器 Static Site Generators](#静态站点生成器-static-site-generators)
    - [超文本传输协议 HTTP](#超文本传输协议-http)
    - [爬虫 Scraping](#爬虫-scraping)
    - [中间件 Middlewares](#中间件-middlewares)
    - [网址 URL](#网址-url)
    - [电子邮件 Email](#电子邮件-email)
    - [文件 Files](#文件-files)
    - [流 Streams](#流-streams)
    - [依赖注入 Dependency Injection](#依赖注入-dependency-injection)
    - [图像 Imagery](#图像-imagery)
    - [测试 Testing](#测试-testing)
    - [持续集成 Continuous Integration](#持续集成-continuous-integration)
    - [文档 Documentation](#文档-documentation)
    - [安全 Security](#安全-security)
    - [密码 Passwords](#密码-passwords)
    - [代码分析 Code Analysis](#代码分析-code-analysis)
    - [Architectural Architectural](#architectural-architectural)
    - [调试和分析 Debugging and Profiling](#调试和分析-debugging-and-profiling)
    - [构建工具 Build Tools](#构建工具-build-tools)
    - [任务运行器 Task Runners](#任务运行器-task-runners)
    - [导航 Navigation](#导航-navigation)
    - [资源管理 Asset Management](#资源管理-asset-management)
    - [地理位置 Geolocation](#地理位置-geolocation)
    - [日期和时间 Date and Time](#日期和时间-date-and-time)
    - [事件 Event](#事件-event)
    - [日志 Logging](#日志-logging)
    - [电子商务 E-commerce](#电子商务-e-commerce)
    - [PDF PDF](#pdf-pdf)
    - [Office Office](#office-office)
    - [数据库 Database](#数据库-database)
    - [迁移 Migrations](#迁移-migrations)
    - [NoSQL NoSQL](#nosql-nosql)
    - [队列 Queue](#队列-queue)
    - [搜索 Search](#搜索-search)
    - [命令行 Command Line](#命令行-command-line)
    - [身份验证和授权 Authentication and Authorization](#身份验证和授权-authentication-and-authorization)
    - [标记 Markup](#标记-markup)
    - [字符串 Strings](#字符串-strings)
    - [数字 Numbers](#数字-numbers)
    - [过滤和验证 Filtering and Validation](#过滤和验证-filtering-and-validation)
    - [API API](#api-api)
    - [缓存 Caching](#缓存-caching)
    - [数据结构和存储 Data Structure and Storage](#数据结构和存储-data-structure-and-storage)
    - [通知 Notifications](#通知-notifications)
    - [部署 Deployment](#部署-deployment)
    - [国际化和本地化 Internationalisation and Localisation](#国际化和本地化-internationalisation-and-localisation)
    - [第三方API Third Party APIs](#第三方api-third-party-apis)
    - [扩展 Extensions](#扩展-extensions)
    - [杂项 Miscellaneous](#杂项-miscellaneous)
- [软件 Software](#软件-software)
    - [PHP安装 PHP Installation](#PHP安装-php-installation)
    - [开发环境 Development Environment](#开发环境-development-environment)
    - [虚拟机 Virtual Machines](#虚拟机-virtual-machines)
    - [集成开发环境(IDE) Integrated Development Environment](#集成开发环境ide-integrated-development-environment)
    - [Web应用 Web Applications](#web应用-web-applications)
    - [基础架构 Infrastructure](#基础架构-infrastructure)
- [资源 Resources](#资源-resources)
    - [PHP网站 PHP Websites](#php网站-php-websites)
    - [其他网站 Other Websites](#其他网站-other-websites)
    - [PHP书籍 PHP Books](#php书籍-php-books)
    - [其他书籍 Other Books](#其他书籍-other-books)
    - [PHP视频 PHP Videos](#php视频-php-videos)
    - [PHP阅读 PHP Reading](#php阅读-php-reading)
    - [PHP内核阅读 PHP Internals Reading](#php内核阅读-php-internals-reading)
    - [PHP杂志 PHP Magazines](#php杂志-php-magazines)
- [贡献](#贡献)

## 依赖管理 Dependency Management
*依赖和包管理库*

* [Climb](https://github.com/vinkla/climb) - 一个Composer版本管理工具
* [Composer Installers](https://github.com/composer/installers) - 一个多框架Composer库安装器
* [Composer](https://getcomposer.org/)/[Packagist](https://packagist.org/) - 一个包和依赖管理器
* [Melody](http://melody.sensiolabs.org/) - 一个用于构建Composer脚本文件的工具
* [Pickle](https://github.com/FriendsOfPHP/pickle) - 一个PHP扩展安装器

## 其他的依赖管理 Dependency Management Extras
*其他的相关依赖管理*

* [Composed](https://github.com/joshdifabio/composed) - 一个在运行时解析你项目Composer环境的库
* [Composer Checker](https://github.com/silpion/composer-checker) - 一个校验Composer配置的工具
* [Composer Merge Plugin](https://github.com/wikimedia/composer-merge-plugin) - 一个用于合并多个composer.json文件的Composer插件
* [Composition](https://github.com/bamarni/composition) - 一个在运行时检查Composer环境的库
* [NameSpacer](https://github.com/ralphschindler/Namespacer) - 一个转化下划线到命名空间的库
* [Patch Installer](https://github.com/goatherd/patch-installer) - 一个使用Composer安装补丁的库
* [Prestissimo](https://github.com/hirak/prestissimo) - 一个开启并行安装进程的Composer插件
* [Satis](https://github.com/composer/satis) - 一个静态Composer存储库的生成器
* [Toran Proxy](https://toranproxy.com) - 一个静态Composer存储库和代理

## 框架 Frameworks
*Web开发框架*

* [Aura PHP](http://auraphp.com/) - 一个独立的组件框架
* [CakePHP](http://cakephp.org/) - 一个快速应用程序开发框架 (CP)
* [Laravel 5](https://laravel.com/) - 简洁优雅的PHP Web开发框架 (L5)
* [Nette](https://nette.org) - 另一个由个体组件组成的框架
* [Phalcon](https://phalconphp.com/en/) - 通过C扩展实现的框架
* [PPI Framework 2](http://www.ppi.io) - 一个互操作性框架
* [Symfony 2](http://symfony.com/) - 一个独立组件组成的框架 (SF2)
* [Yii2](https://github.com/yiisoft/yii2/) - 用于开发大型Web应用的高性能PHP框架
* [Zend Framework 2](http://framework.zend.com) - 另一个由独立组件组成的框架 (ZF2)
* [Radar](https://github.com/radarphp/Radar.Adr) - 一个基于PHP的Action-Domain-Responder实现
* [Ice](http://www.iceframework.org/) - 另一个通过C扩展实现的简单快速的PHP框架
* [Phalcon](https://phalconphp.com/en/) - 一个作为C扩展的框架
* [Yaf](http://php.net/manual/zh/book.yaf.php) - 鸟哥的C扩展的框架 

## 其他框架 Framework Extras
*其他Web开发框架*

* [CakePHP CRUD](https://github.com/friendsofcake/crud) - CakePHP的快速应用程序（RAD）插件
* [Knp RAD Bundle](http://rad.knplabs.com/) - Symfony 2的快速应用程序（RAD）包
* [Symfony CMF](https://github.com/symfony-cmf/symfony-cmf) - 一个创建自定义CMS的内容管理框架

## 框架组件 Components
*来自web开发框架的独立组件*

* [CakePHP Plugins](http://plugins.cakephp.org/) - CakePHP插件的目录
* [Hoa Project](http://hoa-project.net/En/) - 另一个PHP组件包
* [League of Extraordinary Packages](https://thephpleague.com/) - 一个PHP软件开发组
* [Symfony2 Components](http://symfony.com/doc/master/components/index.html) - Symfony 2组件
* [Zend Framework 2 Components](https://packages.zendframework.com/) - Zend Framework 2组件

## 微型框架 Micro Frameworks
*微型框架和路由*

* [Bullet PHP](http://bulletphp.com/) - 用于构建REST APIs的微型框架
* [Lumen](https://lumen.laravel.com) - 一个Laravel的微型框架
* [Proton](https://github.com/alexbilbie/Proton) - 一个StackPHP兼容的微型框架
* [Silex](http://silex.sensiolabs.org/) - 基于Symfony2组件的微型框架
* [Slim](http://www.slimframework.com/) - 另一个简单的微型框架

## 其他微型框架 Micro Framework Extras
*其他相关的微型框架和路由*

* [Silex Skeleton](https://github.com/silexphp/Silex-Skeleton) - Silex的项目架构
* [Silex Web Profiler](https://github.com/silexphp/Silex-WebProfiler) - 一个Silex web的调试工具
* [Slim Skeleton](https://github.com/slimphp/Slim-Skeleton) - Slim架构
* [Slim View](https://github.com/slimphp/Slim-Views) - Slim自定义视图的集合

## 路由 Routers
*处理应用路由的库*

* [Fast Route](https://github.com/nikic/FastRoute) - 一个快速路由的库
* [Klein](https://github.com/klein/klein.php) - 一个灵活的路由的库
* [Macaw](https://github.com/NoahBuscher/Macaw) - 一个简单的 PHP 路由器，超级精简、快速而且很性感。
* [Pux](https://github.com/c9s/Pux) - 另一个快速路由的库
* [Route](https://github.com/thephpleague/route) - 一个基于Fast Route的路由的库

## 模板 Templating
*模板化和词法分析的库和工具*

* [Foil](https://github.com/FoilPHP/Foil) - 另一个原生PHP模板库
* [Lex](https://github.com/pyrocms/lex) - 一个轻量级模板解析器
* [MtHaml](https://github.com/arnaud-lb/MtHaml) - 一个HAML模板语言的PHP实现
* [Mustache](https://github.com/bobthecow/mustache.php) - 一个Mustache模板语言的PHP实现
* [Phly Mustache](https://github.com/phly/phly_mustache) - 另一个Mustache模板语言的PHP实现
* [PHPTAL](http://phptal.org/) - 一个[TAL](https://en.wikipedia.org/wiki/Template_Attribute_Language)模板语言的PHP实现
* [Plates](http://platesphp.com/) - 一个原生PHP模板库
* [Smarty](http://www.smarty.net/) - 一个模板引擎
* [Twig](http://twig.sensiolabs.org/) - 一个全面的模板语言
* [Tale Jade](http://jade.talesoft.io/) - Jade模版语言的PHP实现

## 静态站点生成器 Static Site Generators
*用来生成web页面的预处理内容的工具*

* [Couscous](http://couscous.io) - 一个将Markdown转化为漂亮的网站的工具
* [Phrozn](https://github.com/Pawka/phrozn) - 另一个转换Textile，Markdown和Twig为HTML的工具
* [Sculpin](https://sculpin.io) - 转换Markdown和Twig为静态HTML的工具
* [Spress](http://spress.yosymfony.com) - 一个能够将Markdown和Twig转化为HTML的可扩展工具

## 超文本传输协议 HTTP
*用于HTTP的库*

* [Buzz](https://github.com/kriswallsmith/Buzz) - 另一个HTTP客户端
* [Guzzle]( https://github.com/guzzle/guzzle) - 一个全面的HTTP客户端
* [HTTPFul](https://github.com/nategood/httpful) - 一个链式HTTP库
* [PHP VCR](http://php-vcr.github.io/) - 一个录制和重放HTTP请求的库
* [php-curl-class](https://github.com/php-curl-class/php-curl-class) - PHP的Curl类
* [Requests](https://github.com/rmccue/Requests) - 一个简单的HTTP库
* [Retrofit](https://github.com/tebru/retrofit-php) - 一个能轻松创建REST API客户端的库
* [Zend-diactoros](https://github.com/zendframework/zend-diactoros) - PSR-7 HTTP消息实现

## 爬虫 Scraping
*用于网站爬取的库*

* [Embed](https://github.com/oscarotero/Embed) -  一个从web服务或网页中提取的信息的工具
* [Goutte](https://github.com/FriendsOfPHP/Goutte) - 一个简单的web爬取器
* [PHP Spider](https://github.com/mvdbos/php-spider) - 一个可配置和可扩展的PHP web爬虫

## 中间件 Middlewares
*使用中间件构建应用程序的库*

* [PSR7-Middlewares](https://github.com/oscarotero/psr7-middlewares) - 灵感来源于方便的中间件
* [Relay](https://github.com/relayphp/Relay.Relay) - 一个PHP 5.5 PSR-7的中间件调度器
* [Slim Middleware](https://github.com/slimphp/Slim-Middleware) - 一个用于Slim的自定义的中间件的集合
* [Stack](https://github.com/stackphp) - 一个用于Silex/Symfony的可堆叠的中间件的库
* [Zend-stratigility](https://github.com/zendframework/zend-stratigility) - 基于PHP PSR-7之上的中间件之上

## 网址 URL
*解析URL的库*

* [PHP Domain Parser](https://github.com/jeremykendall/php-domain-parser) - 一个本地前缀解析库
* [Purl](https://github.com/jwage/purl) - 一个URL处理库
* [Sabre/uri](https://github.com/fruux/sabre-uri) - 一个URI操作库
* [Uri](https://github.com/thephpleague/uri) - 另一个URL处理库

## 电子邮件 Email
*发送和解析邮件的库*

* [CssToInlineStyles](https://github.com/tijsverkoyen/CssToInlineStyles) - 一个在邮件模板中的内联CSS库
* [Email Reply Parser](https://github.com/willdurand/EmailReplyParser) - 一个邮件回复解析的库
* [Email Validator](https://github.com/nojacko/email-validator) - 一个较小的电子邮件验证库
* [Fetch](https://github.com/tedious/Fetch) - 一个IMAP库
* [Mautic](https://github.com/mautic/mautic) - 邮件营销自动化
* [Nette Mail](https://github.com/nette/mail) - 一个简单优雅的邮件发送模块
* [PHPMailer](https://github.com/PHPMailer/PHPMailer) - 另一个邮件解决方案
* [Stampie](https://github.com/henrikbjorn/Stampie) - 一个邮件服务库，类似于[SendGrid](http://sendgrid.com),[PostMark](https://postmarkapp.com),[MailGun](http://www.mailgun.com)和[Mandrill](http://www.mandrill.com).
* [SwiftMailer](http://swiftmailer.org/) - 一个邮件解决方案

## 文件 Files
*文件处理和MIME类型检测的库*

* [Apache MIME Types](https://github.com/dflydev/dflydev-apache-mime-types) - 一个解析Apache MIME类型的库
* [Canal](https://github.com/dflydev/dflydev-canal) - 一个检测互联网媒体类型的库
* [CSV](https://github.com/thephpleague/csv) - 一个CSV数据处理库
* [Ferret](https://github.com/versionable/Ferret) - 一个MIME检测库
* [Flysystem](https://github.com/thephpleague/Flysystem) - 另一个文件系统抽象层
* [Gaufrette](https://github.com/KnpLabs/Gaufrette) - 一个文件系统抽象层
* [Hoa Mime](https://github.com/hoaproject/Mime) - 另一个MIME检测库
* [Lurker](https://github.com/henrikbjorn/Lurker) - 一个资源跟踪库
* [PHP FFmpeg](https://github.com/PHP-FFmpeg/PHP-FFmpeg/) - 一个用于[FFmpeg](http://www.ffmpeg.org/)视频包装的库
* [PHP File Locator](https://github.com/kherge-abandoned/php-file-locator) - 一个在大型项目中定位文件的库

## 流 Streams
*处理流的库*

* [Streamer](https://github.com/fzaninotto/Streamer) - 一个简单的面向对象的流包装库

## 依赖注入 Dependency Injection
*实现依赖注入设计模式的库*

* [Acclimate](https://github.com/jeremeamia/acclimate-container) - 一个依赖注入容器和服务定位的通用接口
* [Auryn](https://github.com/rdlowrey/Auryn) - 一个递归的依赖注入容器
* [Container](https://github.com/thephpleague/container) - 另一个可伸缩的依赖注入容器
* [PHP-DI](http://php-di.org/) - 一个支持自动装配和PHP配置的依赖注入容器
* [Pimple](http://pimple.sensiolabs.org/) - 一个小的依赖注入容器
* [Symfony DI](https://github.com/symfony/dependency-injection) - 一个依赖注入容器组件 (SF2)

## 图像 Imagery
*处理图像的库*

* [Color Extractor](https://github.com/thephpleague/color-extractor) - 一个从图像中提取颜色的库
* [GIF Creator](https://github.com/Sybio/GifCreator) - 一个通过多张图片创建GIF动画的库
* [GIF Frame Extractor](https://github.com/Sybio/GifFrameExtractor) - 一个提取GIF动画帧信息的库
* [Glide](https://github.com/thephpleague/glide) - 一个按需处理图像的库
* [Imagine](http://imagine.readthedocs.org/en/latest/index.html) - 一个图像处理库
* [Image Hash](https://github.com/jenssegers/imagehash) - 一个用于生成图像哈希感知的库
* [Image Optimizer](https://github.com/psliwa/image-optimizer) - 一个优化图像的库
* [Image With Text](https://github.com/nmcteam/image-with-text) - 一个在图像中嵌入文本的库
* [Imagine](http://imagine.readthedocs.org/en/latest/index.html) - 一个图像处理库
* [Intervention Image](https://github.com/Intervention/image) - 另一个图像处理库
* [PHP Image Workshop](https://github.com/Sybio/ImageWorkshop) - 另一个图像处理库
* [PHPThumb](https://github.com/masterexploder/PHPThumb) - 缩略图处理库
* [Phpqrcode](https://github.com/t0k4rt/phpqrcode) - 二维码生成库
* [QrCode](https://github.com/endroid/QrCode) - 另一个二维码生成库

## 测试 Testing
*测试代码和生成测试数据的库*

* [Alice](https://github.com/nelmio/alice) - 富有表现力的一代库
* [AspectMock](https://github.com/Codeception/AspectMock) - 一个PHPUnit/Codeception的模拟框架。
* [Atoum](https://github.com/atoum/atoum) - 一个简单的测试库
* [Behat](http://docs.behat.org/en/v2.5/) - 一个行为驱动开发（BDD）测试框架
* [Codeception](https://github.com/Codeception/Codeception) - 一个全栈测试框架
* [DBUnit](https://github.com/sebastianbergmann/dbunit) - 一个PHPUnit的数据库测试库
* [Faker](https://github.com/fzaninotto/Faker) - 一个伪数据生成库
* [HTTP Mock](https://github.com/InterNations/http-mock) - 一个在单元测试模拟HTTP请求的库
* [Kahlan](https://github.com/crysalead/kahlan) - 全栈Unit/BDD测试框架，内置stub，mock和代码覆盖率的支持
* [Locust](http://locust.io/) - 一个Python开发的现代负载测试库
* [Mink](http://mink.behat.org/en/latest/) - Web验收测试
* [Mockery](https://github.com/padraic/mockery) - 一个用于测试的模拟对象的库
* [ParaTest](https://github.com/brianium/paratest) - 一个PHPUnit的并行测试库
* [Peridot](https://github.com/peridot-php/peridot) - 一个事件驱动开发的测试框架
* [Phake](https://github.com/mlively/Phake) - 另一个用于测试的模拟对象的库
* [Pho](https://github.com/danielstjules/pho) - 另一个行为驱动开发测试框架
* [PHPSpec](https://github.com/phpspec/phpspec) - 一个基于功能点设计的单元测试库
* [PHPUnit](https://github.com/sebastianbergmann/phpunit) - 一个单元测试框架
* [Prophecy](https://github.com/phpspec/prophecy) - 一个可选度很高的模拟框架
* [Samsui](https://github.com/mauris/samsui) - 另一个伪数据生成库
* [VFS Stream](https://github.com/mikey179/vfsStream) - 一个用于测试的虚拟文件系统流的包装器
* [VFS](https://github.com/adlawson/php-vfs) - 另一个用于测试虚拟的文件系统

## 持续集成 Continuous Integration
*持续集成的库和应用*

* [GitlabCi](https://about.gitlab.com/gitlab-ci/) - 使用GitLab CI测试、构建、部署你的代码，像TravisCI
* [Jenkins](https://jenkins.io/index.html) - 一个[PHP支持](http://jenkins-php.org/index.html)的持续集成平台
* [JoliCi](https://github.com/jolicode/JoliCi) - 一个用PHP编写的由Docker支持的持续集成的客户端
* [PHPCI](https://www.phptesting.org/) - 一个PHP的开源的持续集成平台
* [SemaphoreCI](https://semaphoreci.com/) - 一个开放源码和私人项目的持续集成平台
* [Shippable](https://app.shippable.com/) - 一个基于开源和私人项目持续集成平台的docker
* [Sismo](http://sismo.sensiolabs.org/) - 一个持续测试的服务库
* [Travis CI](https://travis-ci.org/) - 一个持续集成平台
* [Wercker](http://wercker.com/) - 一个持续集成平台

## 文档 Documentation
*生成项目文档的库*

* [APIGen](https://github.com/apigen/apigen) - 另一个API文档生成器
* [Daux.io](https://github.com/justinwalsh/daux.io) - 一个使用Markdown文件的文档生成器
* [PHP Documentor 2](https://github.com/phpDocumentor/phpDocumentor2) - 一个API文档生成器
* [PhpDox](http://phpdox.de/) - 一个PHP项目的文档生成器（不限于API文档）
* [Sami](https://github.com/FriendsOfPHP/Sami) - 一个API文档生成器

## 安全 Security
*生成安全的随机数，加密数据，扫描漏洞的库*

* [Halite](https://paragonie.com/project/halite) - 一个简单的使用[libsodium](https://github.com/jedisct1/libsodium)的加密库
* [HTML Purifier](https://github.com/ezyang/htmlpurifier) - 一个兼容标准的HTML过滤器
* [IniScan](https://github.com/psecio/iniscan) - 一个扫描PHP INI文件安全的库
* [jose](https://github.com/namshi/jose) - JSON签名和加密的库
* [Optimus](https://github.com/jenssegers/optimus) - 基于Knuth乘法散列方法的身份混淆工具
* [PHP Encryption](https://github.com/defuse/php-encryption) - 一个安全的PHP加密库
* [PHP IDS](https://github.com/PHPIDS/PHPIDS) - 一个结构化的PHP安全层
* [PHP SSH](https://github.com/Herzult/php-ssh) - 一个试验的面向对象的SSH包装库
* [PHPSecLib](http://phpseclib.sourceforge.net/) - 一个纯PHP安全通信库
* [RandomLib](https://github.com/ircmaxell/RandomLib) - 一个生成随机数和字符串的库
* [SecurityMultiTool](https://github.com/padraic/SecurityMultiTool) - 一个PHP安全库
* [SensioLabs Security Check](https://security.sensiolabs.org/) - 一个为检查Composer依赖提供安全建议的web工具
* [TCrypto](https://github.com/timoh6/TCrypto) - 一个简单的键值加密存储库
* [True Random](https://github.com/pixeloution/true-random) - 使用[www.random.org](https://www.random.org/)生成随机数的库
* [VAddy](http://vaddy.net) - 一个持续安全的web应用测试平台
* [Zed](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project) - 一个集成的web应用渗透测试工具

## 密码 Passwords
*处理和存储密码的库和工具*

* [GenPhrase](https://github.com/timoh6/GenPhrase) - 一个随机生成安全密码哈希的库
* [Password Compat](https://github.com/ircmaxell/password_compat) - 一个新的PHP5.5密码函数的兼容库
* [Password Policy](https://github.com/ircmaxell/password-policy) -  一个PHP和JavaScript的密码策略库
* [Password Validator](https://github.com/jeremykendall/password-validator) - 一个校验和升级密码哈希的库
* [Password-Generator](https://github.com/hackzilla/password-generator) - 一个生成随机密码的PHP库
* [PHP Password Lib](https://github.com/ircmaxell/PHP-PasswordLib) - 一个生成和校验密码的库
* [phpass](http://www.openwall.com/phpass/) - 一个便携式的密码哈希框架
* [Zxcvbn PHP](https://github.com/bjeavons/zxcvbn-php) - 一个基于Zxcvbn JS的现实的PHP密码强度估计库

## 代码分析 Code Analysis
*分析，解析和处理代码库的库和工具*

* [Athletic](https://github.com/polyfractal/athletic) - 一个基于注释的基准检测库
* [Code Climate](https://codeclimate.com) - 一个自动代码审查工具
* [Dissect](https://github.com/jakubledl/dissect) - 一个词法和语法分析的工具集合
* [Exakat](http://www.exakat.io) - 一个PHP的静态分析引擎
* [GrumPHP](https://github.com/phpro/grumphp) - 一个用来保护代码质量的Composer插件
* [Mondrian](https://github.com/Trismegiste/Mondrian) - 使用图论的代码分析工具
* [PHP Analyser](https://github.com/scrutinizer-ci/php-analyzer) - 一个分析PHP代码查找缺陷和错误的库
* [PHP Code Sniffer](https://github.com/squizlabs/PHP_CodeSniffer) - 一个检测PHP、CSS和JS代码标准冲突的库
* [PHP CS Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) - 一个编码标准库
* [PHP Manipulator](https://github.com/schmittjoh/php-manipulator) - 一个分析和修改PHP源代码的库
* [PHP Mess Detector](https://phpmd.org/) - 一个扫描代码缺陷，次优代码，未使用的参数等等的库。
* [PHP Metrics](https://github.com/phpmetrics/PhpMetrics) - 一个静态测量库
* [PHP Parser](https://github.com/nikic/PHP-Parser) - 一个PHP编写的PHP解析器
* [PHP Refactoring Browser](https://github.com/QafooLabs/php-refactoring-browser) - 一个重构PHP代码的命令行工具集
* [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker) - 一个比较两个源集和确定适当的应用语义版本的命令行实用程序
* [PHPCheckstyle](https://github.com/PHPCheckstyle/phpcheckstyle) - 一个帮助遵守特定的编码惯例的工具
* [PHPCPD](https://github.com/sebastianbergmann/phpcpd) - 一个检测复制和粘贴代码的库
* [PhpDependencyAnalysis](https://github.com/mamuz/PhpDependencyAnalysis) - 一个创建可定制依赖图的工具
* [PHPLOC](https://github.com/sebastianbergmann/phploc) - 一个快速测量PHP项目大小的工具
* [PHPQA](https://github.com/EdgedesignCZ/phpqa) - 一个用于运行质量保证工具的工具(phploc, phpcpd, phpcs, pdepend, phpmd, phpmetrics).
* [PHPPHP](https://github.com/ircmaxell/PHPPHP) - 一个PHP实现的PHP虚拟机
* [PHPSandbox](https://github.com/fieryprophet/php-sandbox) - 一个PHP沙盒环境
* [Scrutinizer](https://scrutinizer-ci.com/) - 一个审查PHP代码的web工具
* [UBench](https://github.com/devster/ubench) - 一个简单的微型基准检测库

## Architectural Architectural
*相关的设计模式库，组织代码编程的方法和途径*

* [Compose](https://github.com/igorw/compose) - 一个功能组合库
* [Design Patterns PHP](https://github.com/domnikl/DesignPatternsPHP) - 一个使用PHP实现的设计模式存储库
* [Finite](http://yohan.giarel.li/Finite/) - 一个简单的PHP有限状态机
* [Functional PHP](https://github.com/lstrojny/functional-php) - 一个函数式编程库
* [Galapagos](https://github.com/endel/galapagos) - 语言转换进化
* [Iter](https://github.com/nikic/iter) - 一个使用生成器提供迭代原语的库
* [Monad PHP](https://github.com/ircmaxell/monad-php) - 一个简单Monad库
* [Patchwork](http://antecedent.github.io/patchwork/) - 一个重新定义用户的函数库
* [PHP Option](https://github.com/schmittjoh/php-option) - 一个可选的类型库
* [Pipeline](https://github.com/thephpleague/pipeline) - 一个管道模式的实现
* [Ruler](https://github.com/bobthecow/Ruler) - 一个简单的无状态的生产环境规则引擎
* [RulerZ](https://github.com/K-Phoen/rulerz) - 一个强大的规则引擎和规范模式的实现

## 调试和分析 Debugging and Profiling
*调试和分析代码的库和工具*

* [APM](http://pecl.php.net/package/APM) - 一个收集SQLite/MySQL/StatsD错误信息和统计信息的监控扩展
* [Barbushin PHP Console](https://github.com/barbushin/php-console) - 另一个使用Google Chrome的web调试控制台
* [Blackfire.io](https://blackfire.io) - 一个低开销的代码分析器
* [Kint](https://github.com/raveren/kint) - 一个调试和分析工具
* [PHP Console](https://github.com/Seldaek/php-console) - 一个web调试控制台
* [PHP Debug Bar](http://phpdebugbar.com/) - 一个调试工具栏
* [PHPBench](https://github.com/phpbench/phpbench) - 一个基准测试框架
* [PHPDBG](http://phpdbg.com/) - 一个交互的PHP调试器
* [PHP Console](https://github.com/Seldaek/php-console) - Web调试控制台
* [Tideways.io](https://tideways.io/) - Monitoring and profiling tool
* [Tracy](https://github.com/nette/tracy) - A一个简单的错误检测，写日志和时间测量库
* [xDebug](https://github.com/xdebug/xdebug) - 一个调试和分析PHP的工具
* [XHProf](https://github.com/phacility/xhprof) - 一个最初由Facebook开发的分析工具
* [Z-Ray](http://www.zend.com/en/products/server/z-ray) - 一个调试和配置Zend服务器的工具

## 构建工具 Build Tools
*项目构建和自动化工具*

* [Bob](https://github.com/CHH/bob) - 一个简单的项目自动化工具
* [Box](https://github.com/box-project/box2) - 一个构建PHAR文件的工具
* [Go](https://github.com/kherge-abandoned/php-go) - 一个简单的PHP构建工具
* [Phake](https://github.com/jaz303/phake) - 一个PHP克隆库
* [Phing](http://www.phing.info/) - 一个灵感来自于Apache Ant的PHP项目构建系统

## 任务运行器 Task Runners
*自动运行任务的库*

* [Bldr](http://bldr.io/) - 一个构建在Symfony组件上的PHP任务运行器
* [Jobby](https://github.com/jobbyphp/jobby) - 一个没有修改crontab的PHP定时任务管理器
* [Robo](https://github.com/Codegyre/Robo) - 一个面向对象配置的PHP任务运行器
* [Task](http://taskphp.github.io/) - 一个灵感来源于Grunt和Gulp的纯PHP任务运行器

## 导航 Navigation
*构建导航结构的工具*

* [Cartographer](https://github.com/tackk/cartographer) - 一个站点地图生成库
* [KnpMenu](https://github.com/KnpLabs/KnpMenu) - 一个菜单库

## 资源管理 Asset Management
*管理，压缩和最小化web站点资源的工具*

* [Assetic](https://github.com/kriswallsmith/assetic) - 一个资源管理的管道库
* [JShrink](https://github.com/tedious/JShrink) - 一个JavaScript的最小化库
* [Munee](https://github.com/meenie/munee) - 一个资源优化库
* [Pipe](https://github.com/CHH/pipe) - 另一个资源管理的管道库
* [Puli](https://github.com/puli/repository) - 一个检测资源绝对路径的库

## 地理位置 Geolocation
*地理编码地址和使用纬度经度的库*

* [GeoCoder](http://geocoder-php.org/) - 一个地理编码库
* [GeoJSON](https://github.com/jmikola/geojson) - 一个GeoJSON的实现
* [GeoTools](https://github.com/thephpleague/geotools) - 一个地理工具相关的库
* [PHPGeo](https://github.com/mjaschen/phpgeo) - 一个简单的地理库

## 日期和时间 Date and Time
*处理日期和时间的库*

* [CalendR](http://yohan.giarel.li/CalendR/) - 一个日历管理库
* [Carbon](https://github.com/briannesbitt/Carbon) - 一个简单的日期时间API扩展
* [ExpressiveDate](https://github.com/jasonlewis/expressive-date) - 另一个日期时间API扩展
* [Moment.php](https://github.com/fightbulc/moment.php) - 灵感来源于Moment.js的PHP DateTime处理库，支持国际化

## 事件 Event
*时间驱动或实现非阻塞事件循环的库*

* [Amp](https://github.com/amphp/amp) - 一个事件驱动的不阻塞的I/O库
* [Broadway](https://github.com/qandidate-labs/broadway) - 一个事件源和CQRS(命令查询责任分离)库
* [Cake Event](https://github.com/cakephp/event) - 一个事件调度的库 (CP)
* [Elephant.io](https://github.com/Wisembly/Elephant.io) - 另一个web socket库
* [Evenement](https://github.com/igorw/evenement) - 一个事件调度的库
* [Event](https://github.com/thephpleague/event) - 一个专注于域名事件的库
* [Hoa EventSource](https://github.com/hoaproject/Eventsource) - 一个事件源库
* [Hoa WebSocket](https://github.com/hoaproject/Websocket) - 另一个web socket库
* [Icicle](https://github.com/icicleio/icicle) - 一个支持协同，非阻塞I/O，多线程的异步库
* [Prooph Event Store](https://github.com/prooph/event-store) - 一个持久化事件消息的事件源组件
* [Ratchet](https://github.com/ratchetphp/Ratchet) - 一个web socket库
* [React](https://github.com/reactphp/react) - 一个事件驱动的非阻塞I/O库.
* [Rx.PHP](https://github.com/asm89/Rx.PHP) - 一个reactive扩展库
* [Workerman](https://github.com/walkor/Workerman) - 一个事件驱动的不阻塞的I/O库

## 日志 Logging
*生成和处理日志文件的库*

* [Analog](https://github.com/jbroadway/analog) - 一个基于闭包的微型日志包
* [KLogger](https://github.com/katzgrau/KLogger) - 一个易用的兼容PSR-3的日志类
* [Monolog](https://github.com/Seldaek/monolog) - 一个全面的日志工具
* [SeasLog](https://github.com/Neeke/SeasLog) - 一个高性能的PHP日志系统

## 电子商务 E-commerce
*处理支付和构建在线电子商务商店的库和应用*

* [Money](https://github.com/moneyphp/money) - 一个Fowler金钱模式的PHP实现
* [OmniPay](https://github.com/thephpleague/omnipay) - 一个框架混合了多网关支付处理的库
* [Payum](https://github.com/payum/payum) - 一个支付抽象库
* [Sebastian Money](https://github.com/sebastianbergmann/money) - 另一个处理货币值的库
* [Shopware](https://github.com/shopware/shopware) - 一个可高度定制的电子商务软件
* [Swap](https://github.com/florianv/swap) - 一个汇率库
* [Sylius](http://sylius.org/) - 一个开源的电子商务解决方案
* [Thelia](http://thelia.net/) - 另一个开源的电子商务解决方案

## PDF PDF
*处理PDF文件的库和软件*

* [Mpdf](https://github.com/mpdf/mpdf) - 一个是从UTF-8编码的HTML生成PDF文件的PHP库
* [Dompdf](https://github.com/dompdf/dompdf) - 一个将HTML转换为PDF的工具
* [PHPPdf](https://github.com/psliwa/PHPPdf) - 一个将XML文件转换为PDF和图片的库
* [Snappy](https://github.com/KnpLabs/snappy) - 一个PDF和图像生成器库
* [WKHTMLToPDF](https://github.com/wkhtmltopdf/wkhtmltopdf) - 一个将HTML转换为PDF的工具

## Office Office
*Libraries for working with office suite documents.*

* [ExcelAnt](https://github.com/Wisembly/ExcelAnt) - 一个操作Excel文档的库
* [PHPExcel](https://github.com/PHPOffice/PHPExcel) - 一个处理Excel文档的库
* [PHPPowerPoint](https://github.com/PHPOffice/PHPPresentation) - 一个处理PPT文档的库
* [PHPWord](https://github.com/PHPOffice/PHPWord) - 一个处理Word文档的库

## 数据库 Database
*使用对象关系映射（ORM）或数据映射技术的数据库交互的库*

* [Baum](https://github.com/etrepat/baum) - 一个Eloquent的嵌套集实现
* [Cake ORM](https://github.com/cakephp/orm) - 对象关系映射工具，利用DataMapper模式实现 (CP)
* [Doctrine Extensions](https://github.com/Atlantic18/DoctrineExtensions) - 一个Doctrine行为扩展的集合
* [Doctrine](http://www.doctrine-project.org/) - 一个全面的DBAL和ORM
* [Eloquent](https://github.com/illuminate/database) - 一个简单的ORM(L5)
* [LazyRecord](https://github.com/c9s/LazyRecord) - 一个简单、可扩展、高性能的ORM
* [Medoo](http://medoo.in/) - 一个轻量级的加速开发的ORM
* [Pomm](https://github.com/chanmix51/Pomm) - 一个PostgreSQL对象模型管理器
* [Propel](http://propelorm.org/) - 一个快速的ORM，迁移库和查询构架器
* [ProxyManager](https://github.com/Ocramius/ProxyManager) - 一个为数据映射生成代理对象的工具集
* [RedBean](http://redbeanphp.com/index.php) - 一个轻量级，低配置的ORM
* [Spot2](https://github.com/vlucas/spot2) - 一个MySQL的ORM映射器

## 迁移 Migrations
*帮助管理数据库模式和迁移的库*

* [Doctrine Migrations](http://docs.doctrine-project.org/projects/doctrine-migrations/en/latest/toc.html) - 一个Doctrine的迁移库
* [Migrations](https://github.com/icomefromthenet/Migrations) - 一个迁移管理库
* [Phinx](https://github.com/robmorgan/phinx) - 另一个数据库迁移的管理库
* [PHPMig](https://github.com/davedevelopment/phpmig) - 另一个迁移管理库
* [Ruckusing](https://github.com/ruckus/ruckusing-migrations) - 基于PHP下ActiveRecord的数据库迁移，支持MySQL, Postgres, SQLite

## NoSQL NoSQL
*处理NoSQL后端的库*

* [Monga](https://github.com/thephpleague/monga) - 一个MongoDB抽象库
* [MongoQB](https://github.com/alexbilbie/MongoQB) - 一个MongoDB查询构建库
* [Mongo-php-library](https://github.com/mongodb/mongo-php-library) - MongoDB 官方PHP库
* [PHPMongo](https://github.com/sokil/php-mongo) - 一个MongoDB ORM.

* [Predis](https://github.com/nrk/predis) - 一个功能完整的Redis库
* [Phpredis](https://github.com/phpredis/phpredis) - 另一个功能完整的Redis库

## 队列 Queue
*处理事件和任务队列的库*

* [Bernard](https://github.com/bernardphp/bernard) - 一个多后端抽象库
* [BunnyPHP](https://github.com/jakubkulhan/bunny) - 一个高性能的纯PHP AMQP(RabbitMQ)同步和异步(ReactPHP)库
* [Gearman](http://gearman.info/) - 任务分发系统
* [Pheanstalk](https://github.com/pda/pheanstalk) - 一个Beanstalkd客户端库
* [PHP AMQP](https://github.com/php-amqplib/php-amqplib) - 一个纯PHP AMQP库
* [Php-resque](https://github.com/chrisboulton/php-resque) - 基于redis的消息队列
* [Tarantool Queue](https://github.com/tarantool-php/queue) - PHP绑定Tarantool队列
* [Thumper](https://github.com/php-amqplib/Thumper) - 一个RabbitMQ模式库

## 搜索 Search
*在数据上索引和执行查询的库和软件*

* [Elastica](https://github.com/ruflin/Elastica) - ElasticSearch的客户端库
* [ElasticSearch PHP](https://github.com/elastic/elasticsearch-php) - [ElasticSearch](https://www.elastic.co/)的官方客户端库
* [Solarium](http://www.solarium-project.org/) - [Solr](http://lucene.apache.org/solr/)的客户端库
* [Sphinx Search](https://github.com/ripaclub/sphinxsearch) - Sphinx搜索库，提供SphinxQL索引和搜索的功能
* [SphinxQL query builder](http://foolcode.github.io/SphinxQL-Query-Builder/) - [Sphinx](http://sphinxsearch.com/)搜索引擎的的查询库

## 命令行 Command Line
*关于命令行工具的库*

* [Boris](https://github.com/borisrepl/boris) - 一个微型PHP REPL
* [Cilex](https://github.com/Cilex/Cilex) - 一个构建命令行工具的微型框架
* [CLI Menu](https://github.com/php-school/cli-menu) - 一个构建CLI菜单的库
* [CLIFramework](https://github.com/c9s/CLIFramework) - 一个支持完全zsh／bash、子命令和选项约束的命令行框架，这也归功于phpbrew
* [CLImate](https://github.com/thephpleague/climate) - 一个输出带颜色的和特殊格式的命令行库
* [Commando](https://github.com/nategood/commando) - 另一个简单的命令行选择解析器
* [Cron Expression](https://github.com/mtdowling/cron-expression) - 一个计算cron运行日期的库
* [GetOpt](https://github.com/ulrichsg/getopt-php) - 一个命令行选择解析器
* [GetOptionKit](https://github.com/c9s/GetOptionKit) - 另一个命令行选择解析器
* [Hoa Console](https://github.com/hoaproject/Console) - 另一个命令行库
* [OptParse](https://github.com/CHH/optparse) - 另一个命令行选择解析器
* [Pecan](https://github.com/mcrumm/pecan) - 一个事件驱动和非阻塞的shell
* [PsySH](https://github.com/bobthecow/psysh) - 另一个PHP REPL
* [ShellWrap](https://github.com/MrRio/shellwrap) - -一个简单的命令行包装库
* [Shunt](https://github.com/thephpleague/shunt) - 一个在多台远程机器上并行运行命令行的库

## 定时任务 Crontab 
*定时任务管理 crontab在 PHP 中的相关封装*

* [Cronlingo](https://github.com/ajbdev/cronlingo) - Express crontabs as human friendly phrases
* [Dispatcher](https://github.com/Indatus/dispatcher) - 基于Laravel的定时任务管理
* [Jobby](https://github.com/jobbyphp/jobby) - 一个 PHP 的定时任务管理器
* [Swoole-crontab](https://github.com/osgochina/swoole-crontab) - 基于swoole的定时器程序，支持秒级处理

## 身份验证和授权 Authentication and Authorization
*实现身份验证和授权的库*

* [EvaOAuth](https://github.com/AlloVince/EvaOAuth) - 统一接口的 OAuth 登录 PHP 类库
* [Hawk](https://github.com/dflydev/dflydev-hawk) - 一个Hawk HTTP身份认证库
* [HybridAuth](https://github.com/hybridauth/hybridauth) - 一个开源的社交登陆库
* [Json Web Token](https://github.com/lcobucci/jwt) - 使用JSON Tokens进行身份验证和信息传输
* [Lock](https://github.com/BeatSwitch/lock) - 一种实现访问控制列表（ACL）系统的库
* [OAuth 1.0 Client](https://github.com/thephpleague/oauth1-client) - 一个OAuth 1.0客户端的库
* [OAuth 2.0 Client](https://github.com/thephpleague/oauth2-client) - 一个OAuth 2.0客户端的库
* [OAuth2 Server](http://bshaffer.github.io/oauth2-server-php-docs/) - 另一个OAuth2服务器实现
* [OAuth2 Server](http://oauth2.thephpleague.com/) - 另一个OAuth2服务器实现
* [Opauth](https://github.com/opauth/opauth) - 一个多渠道的身份验证框架
* [PHP oAuthLib](https://github.com/Lusitanian/PHPoAuthLib) - 另一个OAuth库
* [Sentinel Social](https://cartalyst.com/manual/sentinel-social/2.0) - 一个社交网络身份验证库
* [Sentinel](https://cartalyst.com/manual/sentinel/2.0) - 一个混合的身份验证和授权的框架库
* [Sentry](https://github.com/cartalyst/sentry) - 认证和授权系统
* [TwitterOAuth](https://github.com/ruudk/twitteroauth) - 一个Twitter OAuth库
* [TwitterSDK](https://github.com/lyrixx/twitter-sdk) - 一个完全测试的Twitter SDK

## 标记 Markup
*处理标记的库*

* [Cebe Markdown](https://github.com/cebe/markdown) - 一个快速的可扩展的Markdown解析器
* [Ciconia](https://github.com/kzykhys/Ciconia) - 另一个支持Github Markdown风格的Markdown解析器
* [CommonMark PHP](https://github.com/thephpleague/commonmark) - 一个对[CommonMark spec](http://spec.commonmark.org/)全支持的Markdown解析器
* [Decoda](https://github.com/milesj/decoda) - 一个轻量级标记解析库
* [Emoji](https://github.com/heyupdate/Emoji) - 一个把Unicode字符和名称转换为表情符号图片的库
* [HTML to Markdown](https://github.com/thephpleague/html-to-markdown) - 将HTML转化为Markdown
* [HTML5 PHP](https://github.com/Masterminds/html5-php) - 一个HTML5解析和序列化库
* [Parsedown](https://github.com/erusev/parsedown) - 另一个Markdown解析器
* [PHP Markdown](https://github.com/michelf/php-markdown) - 一个Markdown解析器
* [Php-emoji](https://github.com/iamcal/php-emoji) - 一个emoji表情转换库

## 字符串 Strings
*解析和处理字符串的库*

* [Agent](https://github.com/jenssegers/agent) - 一个基于Mobiledetect的桌面／手机端user agent解析库
* [ANSI to HTML5](https://github.com/sensiolabs/ansi-to-html) - 一个将ANSI转化为HTML5的库
* [Color Jizz](https://github.com/mikeemoo/ColorJizz-PHP) - 处理和转换颜色的库
* [Device Detector](https://github.com/piwik/device-detector) - 另一个解析user agent字符串的库
* [Hoa String](https://github.com/hoaproject/String) - 另一个UTF-8字符串库
* [Jieba-PHP](https://github.com/fukuball/jieba-php) - Python的jieba的PHP端口，自然语言处理的中文文本分词
* [Mobile-Detect](https://github.com/serbanghita/Mobile-Detect) - 一个用于检测移动设备的轻量级PHP类(包括平板电脑)
* [Patchwork UTF-8](https://github.com/nicolas-grekas/Patchwork-UTF8) - 一个处理UTF-8字符串的便携库
* [Slugify](https://github.com/cocur/slugify) - 转换字符串到slug的库
* [SQL Formatter](https://github.com/jdorn/sql-formatter/) - 一个格式化SQL语句的库
* [Stringy](https://github.com/danielstjules/Stringy) - 一个多字节支持的字符串处理库
* [Text](https://github.com/kzykhys/Text) - 一个文本处理库
* [UA Parser](https://github.com/tobie/ua-parser/tree/master/php) - 一个解析user agent字符串的库
* [URLify](https://github.com/jbroadway/urlify) - 一个Django中URLify.js的PHP版本
* [UUID](https://github.com/ramsey/uuid) - 生成UUIDs的库

## 数字 Numbers
*处理数字的库*

* [ByteUnits](https://github.com/gabrielelana/byte-units) - 一个在二进制和度量系统中解析,格式化和转换字节单元的库
* [LibPhoneNumber for PHP](https://github.com/giggsey/libphonenumber-for-php) - 一个Google电话号码处理的PHP实现库
* [Hashids.php](https://github.com/ivanakimov/hashids.php) - 用来把整数生成唯一字符串（比如：通过加密解密id来隐藏真实id)
* [Math](https://github.com/moontoast/math) - 一个处理巨大数字的库
* [Numbers PHP](https://github.com/powder96/numbers.php) - 一个处理数字的库
* [PHP Conversion](https://github.com/Crisu83/php-conversion) - 另一个用于度量单位间转换的库
* [PHP Units of Measure](https://github.com/triplepoint/php-units-of-measure) - 一个计量单位转换的库

## 过滤和验证 Filtering and Validation
*过滤和验证数据的库*

* [Cake Validation](https://github.com/cakephp/validation) - 另一个验证库 (CP)
* [DMS Filter](https://github.com/rdohms/DMS-Filter) - 一个注释过滤库
* [Filterus](https://github.com/ircmaxell/filterus) - 一个简单的PHP过滤库
* [ISO-codes](https://github.com/ronanguilloux/IsoCodes) - 一个验证各种ISO和ZIP编码的库(IBAN, SWIFT/BIC, BBAN, VAT, SSN, UKNIN)
* [MetaYaml](https://github.com/romaricdrigon/MetaYaml) - 一个支持YAML,JSON和XML的模式验证库
* [Php-readability](https://github.com/feelinglucky/php-readability) - 内容分析算法
* [Respect Validation](https://github.com/Respect/Validation) - 一个简单的验证库
* [Upload](https://github.com/brandonsavage/Upload) - 一个处理文件上传和验证的库
* [Valitron](https://github.com/vlucas/valitron) - 另一个验证库
* [Volan](https://github.com/serkin/Volan) - 另一个简单的验证库

## REST和API
*开发REST-ful API的库和Web工具*

* [API Platform](https://api-platform.com ) - 暴露出REST API的项目，包含JSON-LD, Hydra格式
* [Apigility](https://github.com/zfcampus/zf-apigility-skeleton) - 一个使用Zend Framework 2构建的API构建器
* [Drest](https://github.com/leedavis81/drest) - 一个将Doctrine实体暴露为REST资源节点的库
* [Fractal](https://github.com/thephpleague/fractal) - [最佳实践]数据返回的统一化处理
* [HAL](https://github.com/blongden/hal) - 一个超文本应用语言(HAL)构建库
* [Hateoas](https://github.com/willdurand/Hateoas) - 一个HOATEOAS REST web服务库
* [Negotiation](https://github.com/willdurand/Negotiation) - 一个内容协商库
* [Restler](https://github.com/Luracast/Restler) - 一个将PHP方法暴露为RESTful web API的轻量级框架
* [Wsdl2phpgenerator](https://github.com/wsdl2phpgenerator/wsdl2phpgenerator) - 一个从SOAP WSDL文件生成PHP类的工具

## 缓存 Caching
*缓存数据的库*

* [Alternative PHP Cache (APC)](http://php.net/manual/en/book.apc.php) - 打开PHP操作码缓存
* [APIx Cache](https://github.com/frqnck/apix-cache) -  一个轻量级的PSR-6缓存
* [CacheTool](https://github.com/gordalina/cachetool) - 一个使用命令行清除apc/opcode缓存的工具
* [Cake Cache](https://github.com/cakephp/cache) - 一个缓存库 (CP)
* [Doctrine Cache](https://github.com/doctrine/cache) - 一个缓存库
* [PhpFastCache](https://github.com/khoaofgod/phpfastcache) - PHP 缓存库 
* [Stash](https://github.com/tedious/Stash) - 另一个缓存库
* [Zend Cache](https://github.com/zendframework/zend-cache) - 另一个缓存库 (ZF2)

## 数据结构和存储 Data Structure and Storage
*实现数据结构和存储技术的库*

* [Ardent](https://github.com/morrisonlevi/Ardent) - 一个数据结构库
* [Cake Collection](https://github.com/cakephp/collection) - 一个简单的集合库 (CP)
* [Collections](https://github.com/italolelis/collections) - 一个PHP的集合抽象库
* [Fractal](https://github.com/thephpleague/fractal) - 一个转换复杂数据结构到JSON输出的库
* [Ginq](https://github.com/akanehara/ginq) - 另一个基于.NET实现的PHP的LINQ库
* [JsonMapper](https://github.com/cweiske/jsonmapper) - 一个将内嵌JSON结构映射为PHP类的库
* [PHP Collections](https://github.com/schmittjoh/php-collection) - 一个简单的集合库
* [PINQ](https://github.com/TimeToogo/Pinq) - 一个基于.NET实现的PHP的LINQ(Language Integrated Query)库
* [Serializer](https://github.com/schmittjoh/serializer) - 一个序列化和反序列化数据的库
* [Totem](https://github.com/Wisembly/Totem) - -一个管理和创建数据交换集的库
* [YaLinqo](https://github.com/Athari/YaLinqo) - 另一个PHP的LINQ库
* [Zend Serializer](https://github.com/zendframework/zend-serializer) - 另一个序列化和反序列化数据的库 (ZF2)

## 通知 Notifications
*处理通知软件的库*

* [JoliNotif](https://github.com/jolicode/JoliNotif) - 一个跨平台的桌面通知库(支持Growl, notify-send, toaster等)
* [Nod](https://github.com/filp/nod) - 一个通知库(Growl等)
* [Notification Pusher](https://github.com/Ph3nol/NotificationPusher) - 一个设备推送通知的独立库
* [Notificato](https://github.com/mac-cain13/notificato) - 一个处理推送通知的库
* [Notificator](https://github.com/namshi/notificator) - 一个轻量级的通知库
* [Php-pushwoosh](https://github.com/gomoob/php-pushwoosh) - 一个使用Pushwoosh REST Web服务轻松推送通知的PHP库

## 部署 Deployment
*项目部署库*

* [Deployer](https://github.com/deployphp/deployer) - 一个部署工具
* [Envoy](https://github.com/laravel/envoy) - 一个用PHP运行SSH任务的工具
* [Plum](https://github.com/aerialls/Plum) - 一个部署库
* [Pomander](https://github.com/tamagokun/pomander) - 一个PHP应用部署工具
* [Rocketeer](https://github.com/rocketeers/rocketeer) - PHP世界里的一个快速简单的部署器
* [Walle-web](https://github.com/meolu/walle-web) - 一个开源的web代码发布管理系统

## 国际化和本地化 Internationalisation and Localisation
*国际化(I18n)和本地化(L10n)的库*

* [Aura Intl](https://github.com/auraphp/Aura.Intl)
* [Cake I18n](https://github.com/cakephp/i18n) - 消息国际化和日期和数字的本地化 (CP)

## 第三方API Third Party APIs
*访问第三方API的库*

* [Amazon Web Service SDK](https://github.com/aws/aws-sdk-php) - PHP AWS SDK官方库
* [Campaign Monitor](http://campaignmonitor.github.io/createsend-php/) - Campaign Monitor官方PHP库
* [Digital Ocean](https://github.com/toin0u/DigitalOcean) - Digital Ocean API接口库
* [Dropbox SDK](https://github.com/dropbox/dropbox-sdk-php) - Dropbox SDK官方PHP库
* [Github](https://github.com/dsyph3r/github-api3-php) - 一个Github API交互库
* [PHP Github API](https://github.com/KnpLabs/php-github-api) - 另一个Github API交互库
* [S3 Stream Wrapper](https://github.com/gwkunze/S3StreamWrapper) - Amazon S3流包装库
* [Stripe](https://github.com/stripe/stripe-php) - Stripe官方PHP库
* [Twilio](https://github.com/twilio/twilio-php) - Twilio官方PHP REST API
* [Twitter OAuth](https://github.com/widop/twitter-oauth) - 一个Twitter OAuth工作流交互库
* [Twitter REST](https://github.com/widop/twitter-rest) - 一个Twitter REST API交互库

## 扩展 Extensions
*帮助构建PHP扩展的库*

* [PHP CPP](http://www.php-cpp.com/) - 一个开发PHP扩展的C++库
* [Zephir](https://github.com/phalcon/zephir) - 用于开发PHP扩展，且介于PHP和C++之间的编译语言

## 杂项 Miscellaneous
*创建一个开发环境的软件*

* [Annotations](https://github.com/doctrine/annotations) - 一个注释库(Doctrine的一部分)
* [Cake Utility](https://github.com/cakephp/utility) - 工具类如Inflector，字符串，哈希，安全和XML (CP)
* [Chief](https://github.com/adamnicholson/Chief) - 一个命令总线库
* [ClassPreloader](https://github.com/ClassPreloader/ClassPreloader) - 一个优化自动加载的库
* [Country List](https://github.com/umpirsky/country-list) - 所有带有名称和ISO 3166-1编码的国家列表
* [Embera](https://github.com/mpratt/Embera) - 一个Oembed消费库
* [Essence](https://github.com/essence/essence) - 一个用于提取网络媒体的库
* [Flux](https://github.com/selvinortiz/flux) - 一个正则表达式构建库
* [Graphviz](https://github.com/alexandresalome/graphviz) - 一个图形库
* [Hprose-PHP](https://github.com/hprose/hprose-php) - 一个很牛的RPC库，现在支持25+种语言
* [JSON Lint](https://github.com/Seldaek/jsonlint) - 一个JSON lint工具
* [JSONPCallbackValidator](https://github.com/willdurand/JsonpCallbackValidator) - 验证JSONP回调的库
* [Jumper](https://github.com/kakawait/Jumper) - 一个远程服务执行库
* [LadyBug](https://github.com/raulfraile/Ladybug) - 一个dumper库
* [Lambda PHP](https://github.com/igorw/lambda-php) - 一个PHP中的Lambda计算解析器
* [LiteCQRS](https://github.com/beberlei/litecqrs-php) - 一个CQRS(命令查询责任分离)库
* [Metrics](https://github.com/beberlei/metrics) - 一个简单的度量API库
* [Nmap](https://github.com/willdurand/nmap) - 一个[Nmap](https://nmap.org/) PHP包装器
* [Opengraph](https://github.com/euskadi31/Opengraph) - 一个开放图库
* [Pagerfanta](https://github.com/whiteoctober/Pagerfanta) - 一个分页库
* [PHP Expression](https://github.com/Kitano/php-expression) - 一个PHP表达式语言
* [PHP PassBook](https://github.com/eymengunay/php-passbook) - 一个iOS PassBook PHP库
* [PHP-GPIO](https://github.com/ronanguilloux/php-gpio) - 一个用于Raspberry PI的GPIO pin的库
* [PHPCR](https://github.com/phpcr/phpcr) - 一个Java内容存储库(JCR)的PHP实现
* [PHPStack](http://dunkels.com/adam/phpstack/) - 一个PHP编写的TCP/IP栈概念
* [print_o](https://github.com/koriym/print_o) - 一个对象图的可视化器
* [Procrastinator](https://github.com/lstrojny/Procrastinator) - 一个运行耗时任务的库
* [Prooph Service Bus](https://github.com/prooph/service-bus) - 轻量级的消息总线，支持CQRS和微服务
* [RMT](https://github.com/liip/RMT) - 一个编写版本和发布软件的库
* [sabre/vobject](https://github.com/fruux/sabre-vobject) - 一个解析VCard和iCalendar对象的库
* [Slimdump](https://github.com/webfactory/slimdump) - 一个简单的MySQL dumper工具
* [Spork](https://github.com/kriswallsmith/spork) - 一个处理forking的库
* [Sslurp](https://github.com/EvanDotPro/Sslurp) - 一个使得SSL处理减少的库
* [SuperClosure](https://github.com/jeremeamia/super_closure) - 一个允许闭包序列化的库
* [Symfony VarDumper](http://symfony.com/doc/current/components/var_dumper/introduction.html) - 一个dumper库(SF2)
* [Underscore](http://anahkiasen.github.io/underscore-php/) - 一个Undersccore JS库的PHP实现
* [Whoops](https://github.com/filp/whoops) - 一个不错的错误处理库

## PHP安装 PHP Installation
*在你的电脑上帮助安装和管理PHP的工具*

* [HomeBrew PHP](https://github.com/Homebrew/homebrew-php) - 一个HomeBrew的PHP通道
* [HomeBrew](http://brew.sh/) - 一个OSX包管理器
* [PHP Brew](https://github.com/phpbrew/phpbrew) - 一个PHP版本管理和安装器
* [PHP Build](https://github.com/php-build/php-build) - 另一个PHP版本安装器
* [PHP Env](https://github.com/CHH/phpenv) - 另一个PHP版本管理器
* [PHP OSX](http://php-osx.liip.ch/) - 一个OSX下的PHP安装器
* [PHP Switch](https://github.com/jubianchi/phpswitch) - 另一个PHP版本管理器
* [VirtPHP](http://virtphp.org/) - 一个创建和管理独立PHP环境的工具

## 开发环境 Development Environment
*创建沙盒开发环境的软件和工具*

* [Ansible](https://www.ansible.com/) - 一个非常简单的编制框架
* [Phansible](http://phansible.com/) - 一个用Ansible构建PHP开发虚拟机的web工具
* [Protobox](http://getprotobox.com/) - 另一个构建PHP开发虚拟机的web工具
* [PuPHPet](https://puphpet.com/) - 一个构建PHP开发虚拟机的web工具
* [Puppet](https://puppet.com/) - 一个服务器自动化框架和应用
* [Vagrant](https://www.vagrantup.com/) - 一个便携的开发环境工具

## 虚拟机 Virtual Machines
*相关的PHP虚拟机*

* [Hack](http://hacklang.org/) - 一个PHP进行无缝操作的HHVM编程语言
* [HHVM](https://github.com/facebook/hhvm) - Facebook出品的PHP虚拟机，Runtime和JIT
* [HippyVM](https://github.com/hippyvm/hippyvm) - 另一个PHP虚拟机

## 集成开发环境(IDE) Integrated Development Environment
*支持PHP的集成开发环境*

* [Eclipse for PHP Developers](https://www.eclipse.org/downloads/) - 一个基于Eclipse平台的PHP IDE
* [Netbeans](https://netbeans.org) - 一个支持PHP和HTML5的IDE
* [PhpStorm](http://www.jetbrains.com/phpstorm/) - 一个商业PHP IDE

## Web应用 Web Applications
*基于Web的应用和工具*

* [3V4L](https://3v4l.org/) - 一个在线的PHP和HHVM shell
* [Adminer](https://www.adminer.org/) - 一个数据库管理工具
* [Cachet](https://github.com/cachethq/cachet) - 开源状态页面系统
* [DBV](http://dbv.vizuina.com/) - 一个数据库版本控制应用
* [Grav](https://github.com/getgrav/grav) - 一个现代的flat－file的CMS
* [MailCatcher](https://github.com/sj26/mailcatcher) - 一个抓取和查看邮件的web工具
* [PHP Queue](https://github.com/CoderKungfu/php-queue) - A一个管理后端队列的应用
* [PhpRedisAdmin](https://github.com/ErikDubbelboer/phpRedisAdmin) - 一个用于管理[Redis](http://redis.io/)数据库的简单web界面
* [PhpPgAdmin](https://github.com/phppgadmin/phppgadmin) - 一个PostgreSQL的web管理工具
* [PhpMyAdmin](https://github.com/phpmyadmin/phpmyadmin) - 一个MySQL/MariaDB的web界面
* [rockmongo](https://github.com/iwind/rockmongo) - MongoDB管理工具

## 基础架构 Infrastructure
*提供PHP应用和服务的基础架构*

* [appserver.io](http://appserver.io/) - 一个用PHP写的多线程的PHP应用服务器
* [php-pm](https://github.com/php-pm/php-pm) - 一个PHP应用的进程管理器、修改器和负载平衡器

## PHP网站 PHP Websites
*PHP相关的有用的网站*

* [Nomad PHP](https://nomadphp.com/) - 一个在线PHP学习资源
* [PHP Best Practices](https://phpbestpractices.org/) - 一个PHP最佳实践指南
* [PHP FIG](http://www.php-fig.org/) - PHP框架交互组
* [PHP Mentoring](http://phpmentoring.org/) - 点对点PHP导师组织
* [PHP School](https://www.phpschool.io/) - 学习PHP的开源资源
* [PHP Security](http://phpsecurity.readthedocs.org/en/latest/index.html) - 一个PHP安全指南
* [PHP The Right Way](http://www.phptherightway.com/) - 一个PHP最佳实践的快速指引手册
* [PHP UG](http://php.ug) - 一个帮助用户定位最近的PHP用户组(UG)的网站
* [PHP Versions](http://phpversions.info/) - 哪些版本的PHP可以用在哪几种流行的Web主机上的列表
* [PHP Weekly](http://www.phpweekly.com/archive.html) - 一个PHP新闻周刊
* [PHPTrends](http://phptrends.com/) - 一个快速增长的PHP类库的概述
* [Securing PHP](http://securingphp.com/) - 一个关于PHP安全和库的建议的简报
* [Seven PHP](http://7php.com/) - 一个PHP社区成员采访的网站

## 其他网站 Other Websites
*web开发相关的有用网站*

* [Atlassian Git Tutorials](https://www.atlassian.com/git/) - 一个Git教程系列
* [Hg Init](http://hginit.com/) - 一个Mercurial教程系列
* [Semantic Versioning](http://semver.org/) - 一个解析语义版本的网站
* [Servers for Hackers](https://serversforhackers.com/) - 一个关于服务器管理的新闻通讯
* [The Open Web Application Security Project (OWASP)](https://www.owasp.org/index.php/Main_Page) - 一个开放软件安全社区
* [WebSec IO](https://websec.io/) - 一个web安全社区资源

## PHP书籍 PHP Books
*PHP相关的非常好的书籍*

* [Functional Programming in PHP](https://www.phparch.com/books/functional-programming-in-php/) - 这本书将告诉你如何利用PHP5.3+的新功能的认识函数式编程的原则
* [Grumpy PHPUnit](https://leanpub.com/grumpy-phpunit) - 一本Chris Hartjes关于使用PHPUnit进行单元测试的书
* [Mastering Object-Orientated PHP](http://www.brandonsavage.net) - 一本Brandon Savage关于PHP面向对象的书
* [Modern PHP New Features and Good Practices](http://shop.oreilly.com/product/0636920033868.do) - 一本Josh Lockhart关于新的PHP功能和最佳做法的书
* [Modernising Legacy Applications in PHP](https://leanpub.com/mlaphp) - 一本Paul M.Jones关于遗留PHP应用进行现代化的书
* [PHP 7 Upgrade Guide](https://leanpub.com/php7) - 一本Colin O'Dell的包含所有PHP 7功能和改变的书
* [PHP Pandas](http://daylerees.com/php-pandas/) - 一本Dayle Rees关于如何学习写PHP的书
* [Scaling PHP Applications](http://www.scalingphpbook.com) - 一本Steve Corona关于扩展PHP应用程序的电子书
* [Securing PHP: Core Concepts](https://leanpub.com/securingphp-coreconcepts) - 一本Chris Cornutt关于PHP常见安全条款和实践的书
* [Signaling PHP](https://leanpub.com/signalingphp) - 一本Cal Evans关于在CLI脚本捕获PCNTL信号的书
* [The Grumpy Programmer's Guide to Building Testable PHP Applications](https://leanpub.com/grumpy-testing) - 一本Chris Hartjes关于构建PHP应用程序测试的书
* [XML Parsing with PHP](https://www.phparch.com/books/xml-parsing-with-php/) - 这本书涵盖的解析和验证XML文档，利用XPath表达式，使用命名空间，以及如何创建和修改XML文件的编程

## 其他书籍 Other Books
*与一般计算和web开发相关的书*

* [Elasticsearch: The Definitive Guide](https://www.elastic.co/guide/index.html) - Clinton Cormley和Zachary Tong编写的与Elasticsearch工作的一本指南
* [Eloquent JavaScript](http://eloquentjavascript.net/) - Marijin Haverbeke关于JavaScript编程的一本书
* [Head First Design Patterns](http://www.headfirstlabs.com/books/hfdp/) - 解说软件设计模式的一本书
* [Pro Git](https://git-scm.com/book/en/v2) - Scott Chacon和Ben Straub关于Git的一本书
* [The Linux Command Line](http://linuxcommand.org/tlcl.php) - William Shotts关于Linux命令行的一本书
* [The Tangled Web — Securing Web Applications](http://www.amazon.com/The-Tangled-Web-Securing-Applications/dp/1593273886) - Michal Zalewski关于web应用安全的一本书
* [Understanding Computation](http://computationbook.com) - Tom Stuart关于计算理论的一本书
* [Vagrant Cookbook](https://leanpub.com/vagrantcookbook) - Erika Heidi关于创建 Vagrant环境的一本书

## PHP视频 PHP Videos
*PHP相关的非常不错的视频*

* [PHP Town Hall](https://phptownhall.com/) - 一个随意的Ben Edmunds和Phil Sturgeon的PHP播客
* [PHP UK Conference](https://www.youtube.com/user/phpukconference/videos) - 一个PHP英国会议的视频集合
* [Programming with Anthony](https://www.youtube.com/playlist?list=PLM-218uGSX3DQ3KsB5NJnuOqPqc5CW2kW) - Anthony Ferrara的视频系列
* [Taking PHP Seriously](http://www.infoq.com/presentations/php-history) - 来自Facebook Keith Adams 讲述PHP优势

## PHP阅读 PHP Reading
*PHP相关的阅读资料*

* [Composer Primer](http://daylerees.com/composer-primer/) - Composer初级使用
* [Composer Stability Flags](https://igor.io/2013/02/07/composer-stability-flags.html) - 一篇关于Composer稳定性标志的文章
* [Composer Versioning](https://igor.io/2013/01/07/composer-versioning.html) - 一篇关于Composer版本的文章
* [Create Your Own PHP Framework](http://fabien.potencier.org/create-your-own-framework-on-top-of-the-symfony2-components-part-1.html) - 一部Fabien Potencier的关于如何创建你自己的PHP框架的系列文章
* [Don't Worry About BREACH](http://blog.ircmaxell.com/2013/08/dont-worry-about-breach.html) - 一篇关于BREACH攻击和CSRF令牌的文章
* [On PHP 5.3, Lambda Functions and Closures](http://fabien.potencier.org/on-php-5-3-lambda-functions-and-closures.html) - 一篇关于lambda函数和闭包的文章
* [PHP Is Much Better Than You Think](http://fabien.potencier.org/php-is-much-better-than-you-think.html) - 一篇关于PHP语言和生态圈的文章
* [PHP Package Checklist](http://phppackagechecklist.com/) - A checklist for successful PHP package development.
* [PHP Sucks! But I Like It!](http://blog.ircmaxell.com/2012/04/php-sucks-but-i-like-it.html) - 一篇关于PHP利弊的文章
* [Preventing CSRF Attacks](http://blog.ircmaxell.com/2013/02/preventing-csrf-attacks.html) - 一篇阻止CSRF攻击的文章
* [Seven Ways to Screw Up BCrypt](http://blog.ircmaxell.com/2012/12/seven-ways-to-screw-up-bcrypt.html) - 一篇关于纠正BCrypt实现的文章
* [Use Env](http://seancoates.com/blogs/use-env/) - 一篇关于使用unix环境帮助的文章

## PHP内核阅读 PHP Internals Reading
*阅读PHP内核或性能相关的资料*

* [Disproving the Single Quotes Myth](http://nikic.github.io/2012/01/09/Disproving-the-Single-Quotes-Performance-Myth.html) - 一篇关于单，双引号字符串性能的文章
* [How Big Are PHP Arrays (And Values) Really?](http://nikic.github.io/2011/12/12/How-big-are-PHP-arrays-really-Hint-BIG.html) - 一篇关于数组原理的文章
* [How Foreach Works](http://stackoverflow.com/questions/10057671/how-does-foreach-actually-work/14854568#14854568) - StackOverflow关于foreach回答的详情
* [How Long is a Piece of String](http://blog.golemon.com/2006/06/how-long-is-piece-of-string.html) - 一篇关于字符串原理的文章
* [PHP Evaluation Order](https://gist.github.com/nikic/6699370) - 一篇关于PHP评估顺序的文章
* [PHP Internals Book](http://www.phpinternalsbook.com) - 一本由三名核心开发编写的关于PHP内核的在线书
* [PHP RFCs](https://wiki.php.net/rfc) - PHP RFCs主页(请求注解)
* [Print vs Echo, Which One is Faster?](http://fabien.potencier.org/print-vs-echo-which-one-is-faster.html) - 一篇关于打印和echo性能的文章
* [The PHP Ternary Operator. Fast or Not?](http://fabien.potencier.org/the-php-ternary-operator-fast-or-not.html) - 一篇关于三元操作性能的文章
* [Understanding OpCodes](http://blog.golemon.com/2008/01/understanding-opcodes.html) - 一篇关于opcodes的文章
* [When Does Foreach Copy?](http://nikic.github.io/2011/11/11/PHP-Internals-When-does-foreach-copy.html) - 一篇关于foreach原理的文章
* [Why Objects (Usually) Use Less Memory Than Arrays](https://gist.github.com/nikic/5015323) - 一篇关于对象和数组原理的文章
* [You're Being Lied To](http://blog.golemon.com/2007/01/youre-being-lied-to.html) - 一篇关于内核ZVALs的文章

## PHP杂志 PHP Magazines
*有趣的PHP相关的杂志*

* [php[architect]](https://www.phparch.com/magazine/) - 一个致力于PHP的月更的杂志

### 本博客参考一下资料整理
-- [awesome-php](https://github.com/ziadoz/awesome-php)