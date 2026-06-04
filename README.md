# PDF 文件夹

这个文件夹用来存放你的项目 PDF 文件。

## 使用方法

1. 把你的项目 PDF 文件放到这个文件夹里
2. 在 `src/content.js` 里修改 PDF 路径

## 当前需要的文件

根据 `src/content.js` 的默认配置，你需要准备以下 PDF 文件：

- `project01.pdf` - 项目01完整作品集
- `project02.pdf` - 项目02完整作品集
- `project03.pdf` - 项目03完整作品集

## 示例

如果你有一份 PDF 叫 `my-project.pdf`：

1. 把 PDF 放到这个文件夹（`public/pdfs/my-project.pdf`）
2. 在 `src/content.js` 里写：

```javascript
pdfUrl: "/pdfs/my-project.pdf"
```

## 注意事项

- 确保 PDF 文件名和 `content.js` 里的 `pdfUrl` 完全一致
- PDF 会直接在弹窗中加载，无需额外配置
- 如果 PDF 加载失败，弹窗会显示提示信息