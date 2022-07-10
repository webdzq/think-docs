# 微前端相关内容

- 为了解决巨石应用问题，借助服务端微服务的概念，引入了微前端的架构设计。通过统一入口，共享部分能力，实现一处访问，查看多个系统的效果，从技术上能够共享登录，实现系统间通信。主要特点是各个子应用可以独立开发，独立部署，独立运行，与技术栈无关。
- 目前比较流行的有`single-spa`，`qiankun`，umi，vite，`webpack5`等技术方案。

当然，实现方案很多，如iframe，ssr, 通过BFF(服务于前端的后端，如express，`nestjs`，eggjs等)方式，通过nginx等。

## 文档地址

- single-spa：<https://single-spa.js.org/>
- umi:<https://umijs.org/docs/max/micro-frontend>
- 乾坤：<https://qiankun.umijs.org/zh/guide>
- vite:<https://vitejs.cn/guide/>
- webpack5:<https://webpack.docschina.org/concepts/>



  