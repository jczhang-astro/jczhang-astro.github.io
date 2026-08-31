# Jiachang Zhang 个人网站：GitHub 使用说明

这个仓库已经按 al-folio v1.0 配置好，可以由 GitHub 自动构建和发布。
你不需要在自己的电脑上安装 Ruby、Jekyll 或 Docker。

## 第一步：修改 GitHub 用户名

打开 `_config.yml`，找到：

```yaml
url: https://YOUR-GITHUB-USERNAME.github.io
baseurl:
```

把 `YOUR-GITHUB-USERNAME` 换成你的 GitHub 用户名。`baseurl:` 保持为空，
不要删除这一行。

## 第二步：创建 GitHub 仓库

1. 登录 GitHub，点击 **New repository**。
2. 仓库名必须是 `<你的用户名>.github.io`。
   例如用户名是 `jiachangzhang`，仓库名就是
   `jiachangzhang.github.io`。
3. 建议设为 **Public**。
4. 不要勾选自动创建 README、`.gitignore` 或 License。

## 第三步：上传本站文件

最简单的方法：

1. 解压我提供的压缩包。
2. 打开刚创建的 GitHub 仓库。
3. 选择 **Add file → Upload files**。
4. 上传解压后的所有文件和文件夹，包括 `.github` 目录。
5. 提交到 `main` 分支。

如果 GitHub 网页没有上传以点号开头的目录，建议使用 GitHub Desktop：

1. 在 GitHub Desktop 中克隆空仓库。
2. 把解压后的全部内容复制到克隆目录。
3. Commit 到 `main`，然后 Push。

## 第四步：开启自动部署

1. 打开仓库的 **Actions** 页面并启用 GitHub Actions。
2. 打开 **Settings → Actions → General → Workflow permissions**。
3. 选择 **Read and write permissions**，保存。
4. 回到 **Actions**，等待 `Deploy site` 运行成功。
5. 成功后仓库会自动出现 `gh-pages` 分支。不要手动修改该分支。
6. 打开 **Settings → Pages**。
7. 在 **Build and deployment** 中选择 **Deploy from a branch**，分支选择
   `gh-pages`，目录选择 `/ (root)`，保存。

几分钟后，网站会出现在：

```text
https://<你的用户名>.github.io
```

以后只要修改 `main` 分支，GitHub 就会自动重新生成网站。

## 已经完成的内容

- 英文首页与研究简介
- Research 页面与 M81F4 当前项目
- 4 篇论文的 BibTeX、DOI、arXiv、出版社和 NASA ADS 链接
- Publications、CV、Talks 页面
- 论文新闻时间线
- ORCID 与公开联系邮箱
- GitHub Pages 自动部署工作流

## 建议以后补充

- 把职业照片保存为 `assets/img/prof_pic.jpg`，然后在
  `_pages/about.md` 中把 `profile.image:` 改为
  `profile.image: prof_pic.jpg`。
- 把正式 CV PDF 放进 `assets/pdf/`，并在 `_pages/cv.md` 中填写
  `cv_pdf` 路径。
- 在 `_data/socials.yml` 中添加 GitHub 用户名和 Google Scholar ID。
- 在 `_pages/talks.md` 中加入已确认的报告、会议和 slides。
- 在 `_projects/1_m81f4.md` 中加入可以公开使用的 light curve、
  Chandra/HST position image 和 flare profile。
- 在 `_data/cv.yml` 中补充博士入学年份、教育经历和技术栈。

## 可选：本地预览

安装 Docker Desktop 后，在仓库根目录运行：

```bash
docker compose pull
docker compose up
```

浏览器打开 <http://localhost:8080>。停止时运行：

```bash
docker compose down
```
