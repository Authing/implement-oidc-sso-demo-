# Implement SSO with OIDC Protocol

# 启动 OIDC provider
```shell
$ cd node-oidc-provider
$ npm install # 安装 node-oidc-provider 依赖
$ cd example
$ node express
```

# 启动两个 Web App

## 安装 http-server

```shell
$ npm install -g http-server
```

## 启动 http-server

```shell
$ http-server .
```

# 打开浏览器

访问 [http://localhost:8080/app1.html](http://localhost:8080/app1.html)

访问 [http://localhost:8080/app2.html](http://localhost:8080/app2.html)
