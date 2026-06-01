# AI Photo Prompts

这是一个用于整理、复用和版本管理 AI 照片提示词的仓库模板。

## 目录结构

```text
ai-photo-prompts/
  prompts/
    portrait/        人像写真
    product/         产品图
    food/            食物摄影
    fashion/         服装与造型
    scene/           场景氛围
  templates/
    prompt-template.md
  references/
    style-notes.md
```

## 推荐命名

提示词文件建议使用：

```text
类别-主题-风格.md
```

示例：

```text
portrait-asian-girl-cinematic.md
food-toast-clean-studio.md
product-perfume-luxury-gold.md
```

## 每条提示词建议包含

- 适用模型：Midjourney、Stable Diffusion、DALL-E、即梦、可灵等
- 中文提示词
- 英文提示词
- 负面提示词
- 参数
- 使用说明
- 示例图路径或链接

## GitHub 使用方式

1. 新建 GitHub 仓库，例如 `ai-photo-prompts`。
2. 把本目录里的文件上传到仓库。
3. 后续每新增一条提示词，就在 `prompts/` 下添加一个 `.md` 文件。
4. 用 GitHub 的搜索功能按关键词查找提示词。

## 本地上传命令

```bash
git init
git add .
git commit -m "Add AI photo prompt library"
git branch -M main
git remote add origin https://github.com/你的用户名/ai-photo-prompts.git
git push -u origin main
```

