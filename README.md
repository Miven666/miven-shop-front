## miven-shop-front
### 基于 Vue 开发的商城前台页面
### 感谢 [Exrick](https://github.com/Exrick) 的开源 [vue-mall](https://github.com/Exrick/xmall-front) 项目提供前端页面及框架支持
### 后端全部重新开发接口，实现后台系统管理，后端接口项目请跳转至 [miven-shop](https://github.com/Miven666/miven-shop) 项目仓库查看
### 新增与优化

### 所用技术
- Vue 2.x
- Vuex
- Vue Router
- [Element UI](http://element.eleme.io/#/zh-CN)
- ES6
- webpack
- axios
- Node.js
- 第三方插件
    - [hotjar](https://github.com/Exrick/xmall/blob/master/study/hotjar.md)：一体化分析和反馈
    - [搜狐畅言评论插件](http://changyan.kuaizhan.com/)垃圾广告评论插件 现已更换 [Gitment](https://github.com/imsun/gitment)

### 本地开发运行
- 启动后端 [miven-shop](https://github.com/Miven666/miven-shop) 项目后，在 `config/index.js` 中修改你的后端接口地址配置
- Gitment评论配置见 [Gitment](https://github.com/imsun/gitment) 使用到的页面为 `thanks.vue`
- `index.html` 中复制粘贴替换你的 [hotjar](https://github.com/Exrick/xmall/blob/master/study/hotjar.md) 代码
- 在项目根文件夹下先后执行命令 `npm install` 、 `npm run dev`
- 商城前台端口默认9999 http://localhost:9999
## 部署
- 先后执行命令 `npm install` 、 `npm run build` 将打包生成的 `dist` 静态文件放置服务器中，若使用Nginx等涉及跨域请配置路由代理
