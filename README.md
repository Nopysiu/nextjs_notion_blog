一款基于notion api + NextJS的博客，发布后可以在notion中进行博客管理

## 使用

### notion
需要去[notion](https://wealthy-spandex-08f.notion.site/72a0620229214dc38358fec81666c372?v=ab1c37eac615436fa6b46dc9e995b2b0)复制我的table，再单击你的notion页面右上角的share按钮，然后复制你的页面链接，拿出你自己的页面ID;
```
// 举个🌰
https://wealthy-spandex-08f.notion.site/72a0620229214dc38358fec81666c372?v=ab1c37eac615436fa6b46dc9e995b2b0
                                        |------------------------------| 这一段就是你的页面ID
```
### fork
然后需要fork本项目并修改目录下的文件 src/pages/index.js 中的user变量参数为你的信息;


### 发布
最后在去[vercel](https://vercel.com/)发布你的项目。

### 举个🌰
我的Blog: https://next-js-notion-blog-nine.vercel.app/
## 其它
使用到的技术：nextJS,notion,[react-notion-x](https://github.com/NotionX/react-notion-x),[react-notion](https://github.com/splitbee/react-notion)

## TODO

- [ ] 主题系统

- [ ] 首页img头像
