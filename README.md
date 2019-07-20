# jetty-demo
用于验证jetty功能的简单demo项目

# How to use?

可以三种方式运行
- mvn jetty:run
- 手动部署war包到jetty的站点目录webapps下
- 导入eclipse，使用插件run-jetty-run运行

## 在docker的jetty容器中运行

```
docker run -it --rm --name  my-jetty -p 80:8080 \
-v /d/Jetty/Jetty-distribution-9.4.19.v20190610/webapps:/var/lib/jetty/webapps \
jetty
```
# Issues

- jetty的内嵌开发代码补充
- 异步servlet的代码补充
