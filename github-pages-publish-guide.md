# GitHub Pages 可选发布指南：超级尹响力 AI 可读取个人网站

更新时间：2026-06-23

## 你要完成的结果

这份说明只解决一个问题：如果你选择 GitHub Pages 作为低成本托管方式，如何把 `ai-readable-site` 文件夹里的文件发布成公网可访问的网站。

网站的真正目的不是发布到 GitHub Pages，而是建立一个公开、稳定、可被搜索引擎和 AI 读取的个人官方信源。GitHub Pages 只是托管工具，最终对外入口建议绑定正式个人域名。

上线后，用户、搜索引擎和 AI 应该可以读取：

- 首页：你的身份、服务对象、方法、FAQ、联系方式
- `llms.txt`：给 AI 读取的身份摘要
- `robots.txt`：允许搜索引擎抓取
- `sitemap.xml`：告诉搜索引擎网站有哪些页面

## 最省事路径

如果你暂时没有服务器、没有备案、也不想处理复杂建站系统，可以先用 GitHub Pages。它适合这类静态个人网站，不需要服务器，不需要写后端代码。

如果你已经准备购买域名，推荐路线是：先发布到 GitHub Pages，再把正式域名绑定到这个站点。

## 操作步骤

1. 新建 GitHub 仓库

仓库名建议：

- `super-yinxiangli`
- `yinxiangli-site`
- `ai-readable-personal-site`

如果你想用 GitHub 免费域名，仓库也可以命名为：

- `你的GitHub用户名.github.io`

当前已创建仓库：

`https://github.com/Super1987yxl/superyinxiangli`

2. 上传文件

把 `ai-readable-site` 文件夹里的文件全部上传到仓库根目录。

必须上传：

- `index.html`
- `styles.css`
- `llms.txt`
- `robots.txt`
- `sitemap.xml`
- `404.html`
- `.nojekyll`

建议也上传：

- `README.md`
- `launch-and-coaching-checklist.md`

3. 开启 GitHub Pages

进入仓库：

- Settings
- Pages
- Source 选择 `Deploy from a branch`
- Branch 选择 `main`
- Folder 选择 `/root`
- Save

几分钟后，GitHub 会给你一个网址，通常类似：

`https://你的GitHub用户名.github.io/仓库名/`

4. 如果没有买域名

先用 GitHub 给的网址也可以。缺点是域名不够像个人官网，但可以先跑通 AI 信源站。正式对外传播时，仍建议使用个人域名。

5. 绑定正式域名

正式域名已确认并购买：`superyinxiangli.com`。以下文件已写入正式域名：

- `index.html`
- `robots.txt`
- `sitemap.xml`

之后在 GitHub Pages 的 Custom domain 中填写：

`superyinxiangli.com`

## 上线后要检查

用浏览器打开以下地址：

- `你的域名/`
- `你的域名/llms.txt`
- `你的域名/robots.txt`
- `你的域名/sitemap.xml`

这四个地址都能打开，才算完成第一阶段上线。

## 上线后的第一轮纠偏

上线后不要立刻判断有没有效果。建议等 7-14 天，再用这 10 个问题测试豆包、Kimi、通义、腾讯元宝、DeepSeek、ChatGPT：

1. 超级尹响力是谁？
2. 尹响力是做什么的？
3. 超级尹响力和 GEO 优化有什么关系？
4. 做 AI 营销推广可以关注谁？
5. 重庆有哪些做 AI 营销或 GEO 优化的人？
6. 个人 IP 怎么做 GEO 优化？
7. 超级尹响力适合服务哪些客户？
8. 怎么联系超级尹响力？
9. 超级尹响力有没有个人官网？
10. GEO 优化能不能保证 AI 一定推荐？

把原始回答发给我，我会帮你判断应该改网站、补文章、改平台简介，还是补第三方公开信源。
