# CAUQR

个人二维码图片仓库，用于给支持 Markdown 的网站引用图片。

## 在 Markdown 中引用

```markdown
![扫码访问](https://cdn.jsdelivr.net/gh/1368202089/CAUQR@main/qr.png)
```

备用地址（GitHub 原始文件）：

```markdown
![扫码访问](https://raw.githubusercontent.com/1368202089/CAUQR/main/qr.png)
```

## 注意事项

- 仓库需保持 **Public**，私有仓库的外部链接无法直接访问。
- 文件名建议使用英文（如 `qr.png`），避免 URL 编码问题。
- jsDelivr 存在缓存，刚上传的文件可能短暂 404，等待 1–2 分钟即可。
- 二维码图片建议不小于 200×200 像素，并保留四周白边，否则影响扫码识别率。
