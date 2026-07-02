# 马志年个人学术主页

这是一个可直接部署到 GitHub Pages 的中文个人主页，面向科研展示与腾讯犀牛鸟开源人才培养计划申请。

## 文件结构

```text
.
├── index.html
├── assets
│   ├── css
│   │   └── style.css
│   └── docs
│       ├── application-tencentdb-agent-memory.pdf
│       └── resume-ma-zhinian.docx
└── README.md
```

## 推荐部署方式

1. 在 GitHub 新建仓库：`ma2hi666.github.io`
2. 将本文件夹内的所有内容上传到仓库根目录。
3. 进入仓库 `Settings -> Pages`，确认 Source 为 `Deploy from a branch`，Branch 选择 `main / root`。
4. 等待 GitHub Pages 构建完成，访问：

```text
https://ma2hi666.github.io/
```

## 后续可更新内容

- 将 `MZ` 占位头像替换为真实头像。
- 补充 GitHub issue / PR 链接。
- 在科研项目有正式公开页面后，给项目标题添加论文或代码链接。
- 若简历改为 PDF，可替换 `assets/docs/resume-ma-zhinian.docx` 并同步修改 `index.html` 中的下载链接。
