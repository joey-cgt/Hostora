# V001 生成记录

- 客户：陈肖恩
- 英文名：Shawn
- Workflow：Workflow_A 主持人封面
- 页面模板：A03 左竖标题 + 横副标题 + 右人物型
- 视觉风格：S05 黑金奢华庆典风
- 画布：1080 × 2160 px，9:16 竖版
- 生成模式：内置图像生成工具，基于模板、风格参考与客户真实照片进行身份保持式生成
- 状态：候选版本，等待用户反馈

## 输入图像及用途

1. `01_页面模板库/A_封面/A03_左竖标题+横副标题_右人物型/structure.png`：强制版式结构参考。
2. `02_视觉风格库/S05_黑金奢华庆典风/reference.jpg`：视觉风格参考，不复制其中人物、文字、标志或多页面结构。
3. `03_客户资料库/客户001_陈肖恩/portraits/照片.png`：唯一人物来源与身份保持对象。

## 最终提示词

```text
Use case: identity-preserve
Asset type: final-quality 9:16 vertical Chinese wedding-host personal brand cover
Primary request: Create the first candidate cover using Image 1 as the mandatory A03 layout, Image 2 only as the S05 luxury black-gold style reference, and Image 3 as the only human source.

Input images:
- Image 1: mandatory structure reference. Preserve its left vertical title, left horizontal subtitle and slogan stack, right portrait area, clear two-column separation, safe margins, and clean bottom extension. Do not reproduce instructional labels, outlines, measurements, or placeholder figure.
- Image 2: style reference only. Apply its refined black, champagne-gold, cinematic luxury ceremony atmosphere. Do not copy its woman, wording, logos, signatures, multi-panel layout, or decorative branding.
- Image 3: identity-critical customer portrait and the only person source. Preserve the exact face, facial proportions, skin character, hairstyle, apparent age, smile, body proportions, black formal suit, white shirt, black tie, hand pose, and professional identity. Do not regenerate or replace the face, change clothing, change expression, add jewelry, or alter the person. Only perform clean cutout, edge refinement, color/light balancing, and background integration.

Canvas and mandatory structure:
- Exact 1080 × 2160 px, vertical 9:16.
- Clear left-information/right-person two-column composition.
- Left text area about 25–35% width.
- Right portrait area about 50–60% width and 60–70% height; head in the upper-right/mid-upper region, torso extending downward; keep a complete readable silhouette and never move the person to the left or center.
- Text and portrait must not overlap. No text on the face or body.
- Preserve the bottom 10–15% as a clean visual extension with decoration/background only and no core information.

Exact text only:
- Main title on the upper-left, largest element, vertical top-to-bottom as exactly three characters: “陈” “肖” “恩”
- Horizontal occupation subtitle: “高级婚礼主持人”
- Small English subtitle: “WEDDING HOST”
- Brand slogan, exactly two lines: “以声音传递温度” / “以仪式珍藏幸福”
- Low-weight English auxiliary text: “SHAWN”
- No other text, duplication, invented characters, placeholder text, logos, QR codes, labels, service lists, statistics, captions, watermarks, or signatures.

Style and scene:
- S05 luxury ceremony branding: 65% deep black/ink-black/dark brown-black, 25% sophisticated champagne gold/warm gold/bronze, 10% ivory or warm-gray typography.
- Restrained high-end five-star hotel ballroom or luxury event-stage depth.
- Cinematic commercial portrait lighting faithful to Image 3, with elegant champagne-gold rim light and controlled local highlights.
- Refined obsidian, brushed champagne metal, crystal bokeh, black lacquer and subtle silk sheen.
- Restrained thin gold lines, elegant geometric framing, subtle crystal particles, soft warm bokeh and gentle curved light structures.
- Mature, warm, professional, elegant, reliable; premium wedding magazine and luxury brand launch quality.

Typography:
- Vertical Chinese name is the strongest element, refined high-end Song serif or restrained ceremonial calligraphic display style, champagne gold or warm ivory, highly legible.
- Horizontal subtitle is smaller, elegant and orderly.
- English uses thin uppercase serif with generous tracking.
- Maintain large dark negative space and clear hierarchy.

Avoid:
- cheap yellow gradients, gaudy gold, excessive ornaments, dense patterns, high saturation, red-dominant palette, e-commerce poster styling, cartoon, cyberpunk
- female styling, entertainment portraiture, exaggerated gesture
- identity drift, new face, changed hair, changed clothing, changed smile, extra accessories, malformed hand
- centered portrait, horizontal main name, reversed layout, complex information modules, core content in bottom extension
```

## 输出处理

内置工具原始输出为等比例 1:2 图像，已采用高质量双三次插值无裁切缩放至模板要求的 1080 × 2160 px；画面内容和版式比例未改变。
