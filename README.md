# zhihu-news
 [![license](https://img.shields.io/github/license/mashape/apistatus.svg)](http://opensource.org/licenses/MIT)
> 这是一个基于Vue全家桶开发的知乎日报WebApp，页面样式主要参考iOS版知乎日报APP。



> 项目github地址：[zhihu-news](https://github.com/zhengziheng/zhihu-news)
> 如果觉得对您有帮助，您可以点右上角给个 star 支持一下，十分感谢！如果有问题，也欢迎提交 issue 一起探讨!


## 技术栈
vue2 + vue-router + axios + vuex + vue-cli 
mint-ui + sass + flex + eslint



## 功能
- [x] 首页
- [x] 启动欢迎页
- [x] 首页滚动到底部加载更多
- [x] 查看新闻详情
- [x] 新闻详情页载入下一篇
- [x] 收藏新闻
- [x] 查看评论
- [x] 短评展开和收缩
- [x] 编写评论页（不能发送到后台）
- [x] 侧边栏
- [x] 查看指定主题新闻
- [x] 查看指定主题下的编辑列表
- [x] 查看某个编辑的个人信息
- [x] 查看收藏新闻

## 项目截图
### 首页
![index.png](./screenshots/index.png)

### 新闻详情页
![newsDetail.png](./screenshots/newsDetail.png)

### 评论查看页
![comment.png](./screenshots/comment.png)

### 编辑个人详情页
![editor.png](./screenshots/editor.png)

###  收藏页
![collect.png](./screenshots/collect.png)

## 项目运行
```bash
# 克隆项目到本地
git clone https://github.com/zhengziheng/zhihu-news.git

# 切换到项目所在文件夹
cd zhihu-news

# 安装依赖
npm install

# 本地开发，开启服务器，浏览器访问 http://localhost:8088即可
npm run dev

# 构建生产
npm run build

```
## 目录结构
```
.
|-- build					// webpack配置文件
|-- config					// 项目打包路径
|-- dist					// 项目部署文件，放在服务器即可正常访问
|-- src						// 源码目录
|	|-- assets				// 资源目录
|	|	|-- images			// 图片目录
|	|	|-- sass			// sass目录
|	|		|-- components		// 组件sass目录
|	|		|-- pages		// 页面sass目录
|	|-- components				// 组件
|	|	|-- LongComment.vue		// 长评组件
|	|	|-- NewsList.vue		// 新闻列表组件
|	|	|-- NewsMenu.vue		// 新闻详情底部菜单组件
|	|	|-- Share.vue			// 新闻详情分享弹框组件
|	|	|-- ShortComment.vue		// 短评组件
|	|	|-- Sidebar.vue			// 侧边栏组件
|	|	|-- Swipe.vue			// 轮播图组件
|	|-- pages				// 页面
|	|	|-- Collect.vue			// 收藏页面
|	|	|-- Comment.vue			// 评论页面
|	|	|-- Editor.vue			// 查看编辑个人信息页面
|	|	|-- EditorList.vue		// 编辑列表页面
|	|	|-- Index.vue			// 首页
|	|	|-- NewsDetail.vue		// 新闻详情页面
|	|	|-- ThemeDetail.vue		// 主题页面
|	|	|-- WriteCommnet.vue		// 编写评论页面
|	|-- router
|	|	|-- index.js			// 路由配置
|	|-- store
|	|	|-- index.js			// vuex配置
|	|	|-- actions.js		// actions
|	|	|-- getters.js		// getters
|	|	|-- mutation-types.js	// mutation常量
|	|	|-- mutations.js		// mutation
|	|	|-- state.js			// state
|	|-- App.vue				// 页面入口文件
|	|-- main.js				// 程序入口文件，加载各种公共组件
|-- static					// 静态文件目录
|	|-- css
|	|	|-- animate.css			// 动画css
|	|	|-- iconfont.css		// 图标字体css
|	|	|-- icontont.ttf		// 图标字体ttf
|	|	|-- iconfont.woff		// 图标字体woff
|	|	|-- news_qa_auto.css		// 页面详情内容css
|	|	|-- reset.css			// 统一浏览器样式css
|-- .babelrc					// ES6语法编译配置
|-- .editorconfig				// 代码编写规格配置
|-- .eslintignore				// 忽略eslint检查文件配置
|-- .eslint.js					// eslint配置文件
|-- .gitattributes				// 修改项目在github显示类型配置文件
|-- .gitignore					// git忽略上传文件
|-- .postcssrc.js
|-- index.html					// 入口html文件
|-- package.json				// 项目及工具的依赖配置文件
|-- README.md					// readme说明
|-- yarn.lock					// yarn文件
.
```


## License
[MIT](http://opensource.org/licenses/MIT)
