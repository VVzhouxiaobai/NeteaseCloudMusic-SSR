## 网易云音乐 React同构直出示例  
 入门示例项目  
 `扫描二维码可以在线查看示例`  
![alt text](https://meibin08.github.io/react-redux/demo.png)

### 功能点
- react 服务端渲染 同构直出，解决了SEO优化、减少渲染等待时间（首屏优化）;
- ！！重点完善了同构数据请求的问题;
- Skeleton Screen -- 骨架屏
- 与网易音乐M站版本完全一致的功能;
- 推荐音乐、热歌榜、搜索等

### 安装依赖包 
- git clone https://github.com/meibin08/NeteaseCloudMusic-SSR.git
- npm install (建议使用cnpm 因部分组件如不能翻墙会安装失败)

### 开发环境
- npm run dev
- 访问http://localhost/#/

### 生成环境
- npm run build
- npm start
- 访问http://localhost/#/

### 鸣谢

- 一直在看同构直出的一些东西，尝试了很多次，最后以失败告终，因为在网上看了很多的文章、示例等，都以概念性的为主，每次看到最后，都是千篇一律----`最后最最重点的服务端数据处理、请求等逻辑没有了`，所以想着弄一个完整的示例，正好偶然的机会又看到了以下几位大神分享的内容，给了很大的启发，非常感谢！
- [NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi"NeteaseCloudMusicApi")
- [React同构直出优化总结](https://github.com/joeyguo/blog"blog")
- [react-isomorphic-boilerplate](https://github.com/chikara-chan/react-isomorphic-boilerplate"react-isomorphic-boilerplate")
- [douban-movie-react-ssr](https://github.com/ibufu/douban-movie-react-ssr"douban-movie-react-ssr")

