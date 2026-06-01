# Preferential CN AI Photo Prompts

偏向中国用户的 AI 照片提示词收藏。  
Chinese-focused AI photo prompt collection.

这个仓库的用法很简单：放一张示例照片，然后把对应提示词写在照片下面。

## 示例 001：商务人像精修（陆抖爆火的商务头像）
注意事项：
1，要修改原始图片类的提示词最好使用 Gemini。
实测后发现，Gemini 的 Nano-Bunana 模型对人物面部识别度较高，生成出来的图片具有更高的辨识度，效果更好
2，人像类生图，喂给AI 3~10 张图片效果更佳，包括但不限于不同角度、不同表情、不同光线等等，如果素材有限，可以多抽卡试几次，以提高面部识别度
### V1｜原图
![修改前素材，示例1](image/001-business-portrait-beforeV1.png)
### V2｜原图
![修改前素材，示例2](image/001-business-portrait-beforeV2.png)


```markdown
### V1｜高端商务头像
![示例照片](图片链接或图片路径)
```

### 中文提示词

```text
中文提示词。
将上传的人像转换为美式专业商务头像风格，同时保留人物原有的面部特征与身份辨识度。要求：半身肖像、蓝色纹理摄影棚背景、柔和自然的棚拍灯光、高分辨率清晰度、真实自然的肤色表现，以及干净优雅的画面构图。人物应穿着商务休闲衬衫，搭配简约精致的领带，整体设计现代、专业且具有高级感。
表情应自然放松、自信亲和，眼神明亮有神，并带有真诚自然的微笑。面部保持清晰锐利对焦，背景略微虚化以增强空间层次感，整体效果精致、专业且具有高端商业摄影质感。
```

### English Prompt

```text
Write the English prompt here.
Example: A young woman wearing modern Chinese-style clothing, standing in a Jiangnan courtyard, soft natural light, realistic photography texture, shallow depth of field, clean composition, premium portrait photo, sharp details.
```

### 负面提示词

```text
低清晰度，模糊，脸部变形，手指错误，多余手指，文字，水印，logo，过度磨皮
```

---

## 新增提示词的方法

复制下面这一段，换成你的图片和提示词即可。

```markdown
## 示例 002：这里写标题

![示例照片](图片链接或图片路径)

### 中文提示词

```text
这里写中文提示词。
```

### English Prompt

```text
Write the English prompt here.
```

### 负面提示词

```text
低清晰度，模糊，脸部变形，手指错误，文字，水印，logo
```
```

## 说明

前面我拆了很多文件，是偏“资料库管理”的做法，适合几百条提示词以后按分类查找。

但你现在这个需求更直接：图片在上面，提示词在下面。这个版本更适合展示和分享。
