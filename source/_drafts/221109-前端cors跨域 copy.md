---
title: 前端cors跨域
date: 2022-11-28 11:53:45
tags:
  - 前端篇
  - JavaScript
categories: 前端篇
keywords: 'cors,跨域,CORS跨域'
---


跨域:从一个域请求另一个域的资源如:
- a.com->b.com


常见的跨域错误:
~~~
Access to fetch at 'http://localhost:3001/' from origin 'http://127.0.0.1:5500' has been blocked by CORS policy: No 'Access-Control-Allow-Origin' header is present on the requested resource. If an opaque response serves your needs, set the request's mode to 'no-cors' to fetch the resource with CORS disabled.
~~~

接口服务端修改响应头