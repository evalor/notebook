# CoRequests

一个使用 `Swoole Coroutine Client` 作为客户端的的轻量级协程 HTTP 请求库，基于优秀的 [Requests for PHP](http://requests.ryanmccue.info/) 项目，面向对象的人性化操作API，屏蔽底层复杂的设置和特性，让开发者可以专注于构造请求本身，为单身汪留出更多的约会时间 (๑•̀ㅂ•́)و✧

CoRequests 不仅复刻了 Requests for PHP 的用法，在此基础上还扩展了更多新特性，更提供一个强大的请求构造工具包，包括 `Curl命令行解析器` `UserAgent生成器` `分步请求构造器` `环形代理池` 等系列辅助工具，助力采集项目，编写简单代码即可享受高性能的协程并发请求