# 学习文档

#### 部署步骤

1. 修改 constants.ts 中的http://121.37.219.159:13001
2. vite build
3. 将 dist 部署到 nginx

#### 配置解释

1. env.development 开发环境配置
2. eslintrc.js 代码规范化提示
3. vite.config.js vite 开发服务器配置

#### 常见问题

##### 变量

https://blog.csdn.net/qq_41636947/article/details/117907448

##### antd 的 css 引入方式

在 index.html 里面引入的 cdn

##### cdn

https://cdn.jsdelivr.net/npm/ant-design-vue@3.2.20/dist/ https://cdn.staticfile.org/ant-design-vue/3.2.20/antd.min.css

#### public 文件夹内容在 build 后会自动打到 dist 中
