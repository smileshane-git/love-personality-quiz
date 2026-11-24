# 你在爱情里属于哪一种人格？｜趣味心理测试

一个无需后端、无需安装依赖的静态网页。包含 20 道选择题、自动计分、4 种结果画像、移动端适配与复制结果摘要功能。

## 本地预览

直接用浏览器打开 `index.html` 即可。

## 发布到 GitHub Pages

1. 在 GitHub 新建一个公开仓库，例如 `love-personality-quiz`。
2. 将本项目中的 `index.html` 和 `README.md` 上传到仓库根目录。
3. 打开仓库 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**。
5. Branch 选择 `main`，目录选择 `/ (root)`，点击 **Save**。
6. 等待 GitHub Pages 部署完成，页面地址通常为 `https://你的用户名.github.io/仓库名/`。

## 自定义

- 页面标题、说明文字和样式均在 `index.html` 内。
- 题目位于 JavaScript 的 `questions` 数组中。
- 四种结果文案位于 `types` 对象中。
- 每题四个选项依次对应 A/B/C/D 四种倾向；如调整选项，请保持每题四项顺序与计分逻辑一致。

## 测试说明

本页面是用于自我探索和娱乐的非临床趣味测试，不是经过标准化验证的心理量表，不提供诊断或关系适配结论。计分方式为 20 题中 A/B/C/D 选项的数量统计；若最高分并列，以作答顺序中最后出现的并列类型作为主结果。
