# Ant Design Pro 动态菜单配置

And Design Pro的菜单分为两部分组成，一部分是src/common/router.js一部分是src/common/menu.js。
router相当于后端的Controller，定义好了项目提供哪些页面以及页面对应的配置。
这部分是死的所以不需要放到model中，因此我只将menu部分放到model中作为动态加载。

实现思路：

- :把原src/common/menu.js下写死的菜单使用model来动态加载。
- :分别把router.js、SiderMenu.js、BasicLayout.js中的menu改为model中的menu。

具体修改文件请看下图

![](https://github.com/herton7362/dynamic-menu-pro/raw/master/git.png)

