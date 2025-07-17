# 图片文件夹说明 / Images Folder Guide

此文件夹包含网站所需的所有图片文件。请按照以下结构组织您的图片：

## 文件夹结构 / Folder Structure

```
images/
├── hero/           # 个人头像 / Profile Avatar
│   └── avatar.png  # 建议尺寸：200x200px
├── links/          # 链接图标 / Link Icons
│   ├── telegram.png    # 建议尺寸：100x100px
│   ├── line.png
│   ├── instagram.png
│   └── wechat.png
├── gallery/        # 第一个相册 / First Gallery
│   ├── photo1.png      # 建议尺寸：500x500px+
│   ├── photo2.png
│   └── ... (最多10张)
└── gallery2/       # 第二个相册 / Second Gallery
    ├── photo1.png
    ├── photo2.png
    └── ... (最多10张)
```

## 图片要求 / Image Requirements

### 头像 (Avatar)
- 文件名：`avatar.png`
- 建议尺寸：200x200px
- 格式：PNG (支持透明背景)
- 描述：用作个人资料头像

### 链接图标 (Link Icons)
- 建议尺寸：100x100px
- 格式：PNG
- 描述：用于社交媒体和联系方式链接

### 相册图片 (Gallery Photos)
- 建议尺寸：500x500px 或更高
- 格式：PNG, JPG
- 描述：展示在相册画廊中的图片

## 添加图片 / Adding Images

1. 将图片文件放入对应的文件夹
2. 在 `index.html` 中的 `siteConfig` 对象中添加或修改图片路径
3. 确保文件名和路径匹配

## 注意事项 / Notes

- 图片文件名区分大小写
- 建议使用描述性的文件名
- 优化图片大小以提高加载速度
- 支持的格式：PNG, JPG, JPEG, GIF

---

**提示**：如果图片不显示，请检查文件路径和文件名是否正确。

**Tip**: If images don't show, please check if file paths and filenames are correct.