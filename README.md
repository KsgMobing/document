# 文档编辑器

基于 OnlyOffice SDK + x2t WebAssembly 的纯浏览器端文档编辑器。

- **支持格式**：Word (.docx)、Excel (.xlsx)、PowerPoint (.pptx)、CSV
- **隐私保护**：文件只在浏览器内处理，**不上传任何服务器**
- **离线可用**：PWA 安装到桌面后可离线使用

## 在线访问

https://ksgmobing.github.io/document/

## 本地开发

```bash
pnpm install
pnpm dev
```

## 部署

推送到 `main` 分支自动触发 GitHub Pages 部署（`.github/workflows/pages-build-site.yml`）。

## 致谢

Fork 自 [ranuts/document](https://github.com/ranuts/document)，原始项目基于 [OnlyOffice](https://github.com/ONLYOFFICE) 开源组件。
