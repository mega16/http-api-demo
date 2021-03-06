# HTTP API Demo

一个演示使用 Spring Boot 实现 HTTP API 的例子。PPT 在工程 doc 目录里。

相关文章：

- [分享开发多个线上项目后总结的 HTTP 接口设计方案](https://www.jitao.tech/blog/2020/01/java-http-api/)
- [如何做 HTTP 接口的访问控制](https://www.jitao.tech/blog/2020/03/java-http-api-auth/)

## 运行方法

运行如下命令，编译运行 demo。

```bash
git clone https://github.com/flmn/http-api-demo.git
cd http-api-demo
./gradlew build
build/libs/http-api-demo-0.0.1.jar
```

## 开发说明

在项目目录运行如下命令，生成 Idea 工程文件。

```bash
./gradlew idea
```

用 Idea 打开 **http-api-demo.ipr** 工程文件。

## !注意事项!

1.1.0 版本增加了使用 redis 保存 session，请确保在 localhost 的 6379 端口运行着 redis，并且没密码。修改配置请参见 config/application.yml 配置文件。

否则项目运行会出错。

## 更多信息

- 请关注公众号: **architect-xnq**

![architect-xnq](https://github.com/flmn/http-api-demo/raw/master/doc/img/mp-qr-code.jpg)

- 或者添加私人微信: **pisystem**

![pisystem](https://github.com/flmn/http-api-demo/raw/master/doc/img/pisystem-qr-code.jpg)
