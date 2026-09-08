# V001 生成记录

- 客户目录：张三
- 客户真实姓名：陈果通
- Workflow：Workflow_A 主持人封面
- 页面模板：A02 左横标题 + 横副标题 + 右人物型
- 视觉风格：S02 红白现代商业品牌风
- 画布：1080 × 2160 px，9:16 竖版
- 生成模式：内置图像生成工具，基于本地模板、风格与客户照片进行身份保持式生成
- 状态：候选版本，等待用户反馈

## 输入图像及角色

1. `01_页面模板库/A_封面/A02_左横标题+横副标题_右人物型/structure.png`：强制版式结构参考。
2. `02_视觉风格库/S02_红白现代商业品牌风/reference.jpg`：视觉风格参考，不复制其中人物、姓名、标语或多页面结构。
3. `03_客户资料库/客户001_张三/portraits/照片.png`：唯一人物来源，身份保持对象。

## 最终提示词

```text
Use case: identity-preserve
Asset type: 9:16 vertical Chinese wedding host personal-brand cover, final design artwork
Primary request: Create the first candidate cover following Image 1's A02 structure, Image 2's S02 visual language, and using the real person from Image 3 as the only human subject.

Input images:
- Image 1: mandatory layout/structure reference. Follow its left-text/right-person placement, spacing, hierarchy, and clean bottom extension area; do not reproduce the instructional annotations.
- Image 2: style reference only. Apply its premium modern red-white corporate campaign look, restrained curves, glass/acrylic/metal highlights, and polished launch-event atmosphere; do not copy its people, names, slogans, logos, or multi-panel layout.
- Image 3: identity-critical customer portrait and the only person source. Preserve the exact face, facial proportions, hairstyle, apparent age, skin character, body proportions, black formal suit, white shirt, black tie, hand pose, and professional identity. Do not regenerate, beautify into a different person, change clothing, add accessories, or alter identity. Only allow clean cutout, lighting/color balancing, edge refinement, and background integration.

Canvas and structure:
- Exact 1080 × 2160 px, vertical 9:16.
- Large clean white field, about 70% white, 20% deep Chinese red, 10% black/silver gray.
- Left text column occupies about 25–35%, right portrait about 50–60%.
- Portrait on the right, head in upper-right, torso extending downward, full visible silhouette within the composition; never center or move left.
- Keep clear separation between all text and the face/body.
- Preserve the lower 10–14% as a clean atmospheric extension with no core information.
- Use only restrained deep-red flowing curves/ring light, translucent glass layers, subtle silver-gray geometry or minimalist architectural linework. Premium, clean, modern, professional, reliable. No complex scene.

Text: Render all text exactly and legibly, without substitutions, duplication, invented content, or stray glyphs.
Main title: “陈果通”
English signature: “JOEY”
Occupation subtitle: “高级婚礼主持人”
English subtitle: “WEDDING HOST”
Brand slogan, exactly two lines:
“以声音传递温度”
“以仪式珍藏幸福”

Typography:
- Main title is the strongest typographic element, horizontal and left-aligned.
- Supporting English uses minimalist sans-serif with careful letter spacing.
- Strong hierarchy and generous whitespace.
- Do not add service lists, tags, cards, statistics, logos, QR codes, extra captions, watermarks, or any unprovided text.

Lighting and finish:
- Bright high-key commercial studio presentation with soft edge light and restrained red reflected light.
- Keep face natural and faithful to Image 3.
- Luxury corporate branding campaign, not wedding-shop advertising, not entertainment portraiture.

Avoid:
- identity drift, regenerated face, changed expression, changed hair, changed clothing, altered hand anatomy, added jewelry
- centered portrait, reversed layout, vertical title, title over face, dense information
- pink girlish styling, black-gold styling, vintage texture, flowers, cartoons, cyberpunk, noisy patterns, cheap e-commerce look
- any text other than the exact specified content
```

## 输出说明

内置工具原始输出为等比例 1:2 图像，已采用高质量双三次插值无裁切缩放至模板要求的 1080 × 2160 px；画面内容与版式比例未改变。
