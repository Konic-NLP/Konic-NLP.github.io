# Luka Homepage

[English README](README.md)

`Luka Homepage` 是一个极简、温暖、响应式的个人主页模板，适合学术主页、研究者主页、个人作品集和实验室成员主页。

这个目录是一个独立模板版本，不依赖仓库根目录下的现有主页文件。你可以直接把 `luka-homepage-template/` 整个复制到一个新仓库中使用。

## 推荐仓库名

- `luka-homepage`
- `luka-homepage-template`
- `luka-academic-homepage`

## 特性

- 纯静态 `HTML / CSS / JS`，无需构建
- 温暖克制的两栏布局，适合学术和个人主页
- 内置深色模式切换
- 已做移动端适配
- 自带 `About`、`Education`、`Experience`、`Projects`、`Publications`、`Awards`
- 容易替换头像、Logo、链接和简历

## 快速开始

### 1. 创建新仓库

在 GitHub 上新建一个仓库，然后把这个目录里的内容复制进去即可。

如果你希望别人可以一键复用，建议在仓库设置里开启 `Template repository`。

### 2. 修改内容

主要编辑这些文件：

- `index.html`：页面内容和结构
- `assets/css/theme-luka.css`：主样式文件
- `assets/img/avatar.svg`：默认头像占位图
- `assets/img/institution.svg`：默认机构 Logo 占位图

### 3. 替换资源

建议替换成你自己的内容：

- 头像：`assets/img/avatar.svg`
- 机构 Logo：`assets/img/institution.svg`
- favicon：`assets/img/favicon.svg`
- 简历链接：修改 `index.html` 中的 `Download my CV`

### 4. 部署到 GitHub Pages

1. 打开仓库 `Settings`
2. 进入 `Pages`
3. 选择 `Deploy from a branch`
4. 选择 `main` 和 `/ (root)`
5. 保存并等待部署完成

## 目录结构

- `index.html`
- `assets/css/font_sans_serif.css`
- `assets/css/theme-luka.css`
- `assets/js/scale.fix.js`
- `assets/img/`
- `assets/cv/`

## 署名与版权

默认页脚包含两行：

1. 你的站点版权信息
2. `Luka Homepage template by Yuheng Yang`

如果你希望保留模板来源，建议保留第二行。

## 许可证

这个目录自带 `LICENSE.md`，方便你把它单独发布成一个独立仓库。
