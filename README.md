# Halo-Gallery

用于 [Halo](https://halo.run/) 博客的图床仓库，按年份归档的图片资源。

## 目录结构

```
Halo图库/
└── 2026/            # 按年份归档
    ├── AITopic_01-0208232827.png
    ├── AITopic_02-0208232810.png
    └── ...
```

当前收录：26 张 PNG + 1 张 JPG（约 115 MB）。

## 引用方式

在 Halo 后台文章、其他 Markdown 编辑器或 HTML 中直接引用：

**jsDelivr CDN（推荐，带缓存、速度快）**

```
https://cdn.jsdelivr.net/gh/jiumooo/Halo-Gallery@main/Halo图库/2026/AITopic_01-0208232827.png
```

**raw 直链（无缓存，适合临时预览）**

```
https://raw.githubusercontent.com/jiumooo/Halo-Gallery/main/Halo图库/2026/AITopic_01-0208232827.png
```

> 中文目录名 `Halo图库` 在部分 CDN / 浏览器中需做 URL 编码：
> `%E5%9B%BE%E5%BA%93`。
> 若遇到 404，请优先尝试编码后的地址。

## 维护约定

- 新增图片放入 `Halo图库/<年份>/`，文件名保持 `名称-时间戳` 格式。
- 单个图片建议压缩到 1 MB 以内（PNG 可用 oxipng / pngquant，JPG 质量 80–85）。
- 仓库为纯图床，不建议在根目录堆积散图。
- 大体积图片会让克隆变慢；只需要单张图片时用上面的直链，不必克隆整个仓库。

## License

图片版权归原作者所有，仅用于本站博客展示。
