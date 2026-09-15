# Workflow_B / B01_S08 / V001

## 生成配置

- 客户：客户001_陈肖恩（陈肖恩 / Shawn）
- Workflow：Workflow_B（主持人个人介绍页）
- 页面模板：B01_顶部介绍+双数据卡片+双人物型
- 视觉风格：S08_香槟雅韵东方婚礼美学风
- 成品尺寸：1080 × 2160 px（1:2 竖版）
- 生成方式：内置图像生成工具；初始结果 887 × 1774 px，等比例标准化至模板尺寸。

## 输入素材与职责

1. `01_页面模板库/B_个人介绍页/B01_顶部介绍+双数据卡片+双人物型/structure.png`：仅控制版式区域与层级。
2. `02_视觉风格库/S08_香槟雅韵东方婚礼美学风/reference.png`：仅控制香槟米白、东方建筑空间、丝绸、柔和光影与编辑风格；不使用参考人物、文字或版式。
3. `03_客户资料库/客户001_陈肖恩/portraits/照片.png`：唯一人物来源；左侧辅助照片及右侧主体均由此照片裁切。

## 已使用且可追溯的客户信息

- 页面标题：关于我
- 姓名：陈肖恩 Shawn
- 身份：厦门婚礼主持人
- 定位：为新人创造高级仪式体验的婚礼主持人
- 理念：以声音传递温度；以仪式珍藏幸福

## 留白项

客户未提供主持年限及主持场次，两张数据卡片仅保留空白卡片结构，不填充数字、单位或指标文字。

## 生成提示词

```text
Create a production-ready 1080 × 2160 px, 1:2 vertical Chinese wedding-host personal introduction page. Use the B01 structure map only for layout, the S08 reference only for champagne-beige oriental architecture, translucent silk, soft editorial light and restrained luxury, and Chen Xiao'en's portrait as the one and only person source.

Preserve Chen Xiao'en's real male facial features, age, hairstyle, body proportions and black tuxedo exactly. Use only clean crops from the supplied portrait: one square head-and-shoulder crop in the left-middle auxiliary-photo block and one large 3/4 torso crop in the right-lower subject block. Do not invent a face, body, clothing, hands, jewelry or another person; do not feminize him.

Keep the B01 order: top centered title and identity, then two equal blank data cards, then left auxiliary photo plus right positioning text, then left feature text plus right main portrait, with a blank bottom 6%. The blank cards must not contain numbers, units, metric labels or placeholder text.

Render only this supplied text: “关于我”; “陈肖恩 Shawn\\n厦门婚礼主持人”; “为新人创造高级仪式体验的\\n婚礼主持人”; “以声音传递温度\\n以仪式珍藏幸福”. Do not add claims, services, tags, QR codes, awards, extra photo subjects or branding. Do not make a phone frame, UI, annotations, structural labels, arrows or watermark.
```
