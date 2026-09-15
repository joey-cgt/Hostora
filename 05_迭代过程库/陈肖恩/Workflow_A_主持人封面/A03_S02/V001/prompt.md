# V001 生成记录

- 客户：陈肖恩
- 英文名：Shawn
- Workflow：Workflow_A 主持人封面
- 页面模板：A03 左竖标题 + 横副标题 + 右人物型
- 视觉风格：S02 红白现代商业品牌风
- 画布：1080 × 2160 px，9:16 竖版
- 生成模式：内置图像生成工具，基于模板、风格参考与客户真实照片进行身份保持式生成
- 状态：候选版本，等待用户反馈

## 输入图像及用途

1. `01_页面模板库/A_封面/A03_左竖标题+横副标题_右人物型/structure.png`：强制版式结构参考。
2. `02_视觉风格库/S02_红白现代商业品牌风/reference.jpg`：视觉风格参考，不复制其中人物、文字、标志或多页面结构。
3. `03_客户资料库/客户001_陈肖恩/portraits/照片.png`：唯一人物来源与身份保持对象。

## 最终提示词

```text
Use case: identity-preserve
Asset type: final-quality 9:16 vertical Chinese wedding-host personal brand cover
Primary request: Create the first candidate cover using Image 1 as the mandatory A03 structure, Image 2 only as the S02 modern red-white commercial style reference, and Image 3 as the only human source.

Input images:
- Image 1: preserve the left vertical title, horizontal subtitle and slogan stack, right portrait area, two-column separation, safe margins, and clean bottom extension. Do not reproduce instructional labels or placeholders.
- Image 2: apply only its premium red-white corporate branding language. Do not copy its person, wording, logos, data panels, signatures, or multi-page composition.
- Image 3: preserve the exact face, facial proportions, skin character, hairstyle, apparent age, smile, body proportions, black formal suit, white shirt, black tie, and hand pose. Do not regenerate the face, change clothing, add accessories, or alter identity. Only allow clean cutout, edge refinement, color/light balancing, and background integration.

Canvas and structure:
- Exact 1080 × 2160 px, vertical 9:16.
- Left information area about 25–35% width; right portrait about 50–60% width and 60–70% height.
- Portrait stays on the right with head in the upper-right/mid-upper area and torso extending downward.
- Text and portrait remain separate; no text over face or body.
- Lower 10–15% is a clean decorative/background extension without core information.

Exact text only:
- Vertical main title, top-to-bottom: “陈” “肖” “恩”
- Horizontal subtitle: “高级婚礼主持人”
- English subtitle: “WEDDING HOST”
- Two-line slogan: “以声音传递温度” / “以仪式珍藏幸福”
- Auxiliary English: “SHAWN”
- No other text, duplicates, invented glyphs, logos, QR codes, lists, statistics, captions, watermarks, or signatures.

S02 style:
- About 70% bright white, 20% deep Chinese red, 10% black/silver-gray.
- Clean premium corporate campaign; modern, powerful, professional, mature and trustworthy.
- High-key studio lighting faithful to Image 3, subtle rim light and restrained red reflection.
- Transparent glass, acrylic, brushed silver metal, glossy paper and translucent film.
- Elegant deep-red flowing curves, restrained ring light, silver-gray geometry and minimal architectural/city linework.
- Spacious background; luxury corporate launch and high-end professional profile quality.

Typography:
- Vertical Chinese name is the strongest element, modern bold Chinese sans-serif or refined brand serif, deep red and highly legible.
- Subtitle is horizontal, smaller and orderly.
- English is minimalist uppercase sans-serif with generous tracking.
- Strong hierarchy, grid discipline and generous white space.

Avoid:
- identity drift, regenerated face, changed hair, smile or clothing, extra accessories, malformed hand
- centered portrait, horizontal main name, reversed layout, overlap, complex modules, core content in bottom extension
- black-gold styling, literary low saturation, girlish pink, ornate wedding-shop decoration, flowers, cartoons, cyberpunk, noisy multicolor or cheap e-commerce styling
```

## 输出处理

内置工具原始输出为等比例 1:2 图像，已采用高质量双三次插值无裁切缩放至模板要求的 1080 × 2160 px；画面内容和版式比例未改变。
