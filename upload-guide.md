# 图片上传说明

## 需要上传到 images/ 目录的文件

请将以下图片文件上传到你的GitHub仓库的 `images/` 目录：

### 1. og-image.jpg (1200x630 像素)
- 用于 Facebook、LinkedIn 分享预览
- 建议: 使用品牌主图或产品展示图
- 如果没有，可以从 Recraft 生成:
  ```
  uv run <recraft脚本路径> generate --prompt "Professional cable tray manufacturing facility with steel cable management systems, industrial warehouse, B2B business, blue and orange color scheme" --style "Photorealism" --filename "og-image.jpg" --size "16:9"
  ```

### 2. twitter-image.jpg (1200x675 像素)
- 用于 Twitter 卡片分享
- 建议: 与 og-image 配合使用相似设计
- 如果没有，可以从 Recraft 生成:
  ```
  uv run <recraft脚本路径> generate --prompt "Jiangsu Yanggang Electrical Equipment logo, cable tray systems, industrial manufacturing, professional B2B, blue and yellow colors" --style "Vector art" --filename "twitter-image.jpg" --size "16:9"
  ```

### 3. logo.png (建议 500x500 像素或 200x200)
- 用于 Organization Schema 中的 logo
- 建议: 透明背景的 PNG 图片
- 可以从 Recraft 生成的矢量图转换:
  ```
  uv run <recraft脚本路径> generate --prompt "YG Electrical logo, cable tray symbol, professional industrial brand" --style "Vector art" --filename "logo.svg"
  ```
  然后使用在线工具将 SVG 转换为 PNG

### 4. favicon-16.png (16x16 像素)

### 5. favicon-32.png (32x32 像素)

### 6. apple-touch-icon.png (180x180 像素)
- 用于 Apple 设备添加到主屏幕图标

---

## 快速获取图片的方法

如果不方便生成，可以：
1. 直接用 Figma/Canva 创建简单图片
2. 从产品图册中选取合适图片
3. 使用图库图片（需有授权）

## 上传后验证

上传后，在浏览器中验证:
- https://ygdqjt.github.io/images/og-image.jpg
- https://ygdqjt.github.io/images/twitter-image.jpg
- https://ygdqjt.github.io/images/logo.png