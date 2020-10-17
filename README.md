# NexT For Hugo

A Hugo theme ported from [NexT](https://github.com/iissnan/hexo-theme-next).

## Description

NexT is a simple and animated theme. I ported it from Hexo to [Hugo](https://gohugo.io/) and used in my blog site.
Thanks for [elkan](https://github.com/elkan1788), I cloned his NexT theme and modified it in my style.
[Preview online](https://luhuachuixue.cf)

## Usage

1. clone latest theme repo: `git clone --depth=1 https://github.com/luhuachuixue/hugo-theme-next.git themes/next`

2. modify config file: `cp themes/next/exampleSite/config.toml .` copy config file to your hugo site's root directory, and modify it according to the actual information for your site.

3. moify article template: `cp themes/next/archetypes/default.md archetypes`

4. add qrcode pictures, which may involve someone's private information in your root static/img directory, and those pictures should be named by: `ali-pay.png`, `qq_qrcode.png`, `qq-pay.png`, `wechat-pay.png`

5. write an article: `hugo new post/first-post.md`

6. start hugo server: `hugo server --disableFastRender --noHTTPCache`

7. browse in a brower: <http://localhost:1313>

## Notes

- **Some of the Hexo's styles are not work now**, because of the difference between the Hugo's template engine and the Hexo's.

- This theme has been tested only in my blog site. Maybe it's not suitable for your requirements, you can customizate it by your preferences.

- Test in Hugo verion: **0.75.1**

## Markdown notes

1. every markdown should start with like this:

```markdown
---
title: "Hello World"
date: "2020-09-11"
tags:
    - 测试
    - 学习
categories:
    - Hugo
toc: true
---
```

2. add `<!--more-->` tag in your markdown for [manual summary splitting](https://gohugo.io/content-management/summaries/#user-defined-manual-summary-splitting).

## License

The [MIT License](LICENSE).