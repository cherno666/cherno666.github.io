# 照片放这里 / Put your photos here

把你们的合照复制到这个文件夹，按数字顺序命名即可，例如：

    1.jpg
    2.png
    3.jpeg
    ...

- 支持扩展名：jpg / jpeg / png / webp / gif
- 相册页 `gallery.html` 会自动读取 `1, 2, 3 ...` 并展示
- 数量不限（默认最多 80 张）
- 想改说明文字，编辑 `gallery.html` 里 `cap.textContent = "照片 " + i;` 这一行即可

注意：图片会被公开访问（GitHub Pages 是公开站），请勿放隐私敏感的照片。
