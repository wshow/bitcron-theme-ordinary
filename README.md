![screenshot.jpg](https://raw.githubusercontent.com/shuibaco/bitcron-theme-ordinary/master/screenshot.jpg)

「庸」(Ordinary)是一个平淡无奇的 Bitcron 主题，基本实现了所有功能。

## 特点

- 网站标题采用中国风的「王汉宗超明体」（仅作用于繁体字）；
- 支持 `分类` 和 `标签`；
- 归档页面包括 `归档` 和 `分类&标签` 目录；
- 支持网站颜色自定义（具体操作在后文说明）；
- 自适应页面，手机浏览体验佳；
- 可显示社交账号
- 优化了评论框
- 只有六个文件

## 安装设置

下载 template 文件夹，放入网站根目录下。

- **标题**：Dashboard → Site → Title / Sub Title
- **每页显示文章数**：Dashboard → Common → Posts Per Page
- **社交账号**：Dashboard → Common → Social ID
- **嵌套评论**：Dashboard → Render → Comments Type: Tree
- **菜单**：Dashboard → Navigation
- **网站相关图片**：Dashboard → Images
- **归档页面显示文章数**：archive.jade 第九行 `limit=30`
- **网站颜色自定义**：style.scss 第一行开始的 `Customize field`。
    + `$mcolor`：main color 主要颜色
    + `$pcolor`：point color 链接等
    + `$bgcolor`：background color 背景颜色
    + `$scolor`：second color 次于主要颜色的第二多被使用的颜色
    + `$tcolor`：text color 文字颜色

## 欢迎赞助

<figure>
    <img src="https://raw.githubusercontent.com/shuibaco/donate/master/alipay.jpg" alt="支付宝二维码" />
    <figcaption>使用支付宝赞助</figcaption>
</figure>