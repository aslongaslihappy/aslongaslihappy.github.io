# 李天恩的学术主页

基于 [Academic Pages](https://github.com/academicpages/academicpages.github.io) 重构的个人学术主页，部署地址为 <https://aslongaslihappy.github.io>。

## 内容结构

- `/_pages/`：首页、论文、项目、博客归档与 CV
- `/_publications/`：论文条目
- `/_portfolio/`：开源项目条目
- `/_posts/`：研究笔记
- `/_sass/layout/_custom.scss`：站点定制样式
- `/_config.yml`：个人信息、导航与站点配置

## 本地预览

安装 Ruby 与 Bundler 后运行：

```bash
bundle install
bundle exec jekyll serve
```

访问 `http://localhost:4000`。GitHub Actions 会在推送或提交 Pull Request 时执行严格构建检查。
