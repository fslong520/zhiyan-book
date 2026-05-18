# 《纸焰》角色绘图 Prompt

---

## 小说封面 Prompt

### 封面构图概念

```
竖向封面构图，2:3比例。

上下分割构图。下方三分之一是纯白洗涤室——颜书瑤赤足站在金属台前，身着银白色战斗服，贴身裁剪露出肩颈与大部份背部的线条，紧身设计完美展现修长身形轮廓，黑发垂落，侧影，冷白调，无影，天花板裂缝贯穿。上方三分之二是深邃墨蓝至暗红的渐变背景，数十张燃烧的书页从下方升起、漂浮、化为灰烬飘散。火焰是暖橙金色，在冷白与墨蓝之间形成一道炽烈的过渡带。灰烬如雪般飘落在洗涤室的边缘。

封面中央横排两个大字——"纸焰"，字体为行楷，墨色但边缘燃着金色的火焰，笔画的末端化为飞灰飘散。

画面有两种气质在交锋：下方的绝对冷静与上方的炽热燃烧。冷白与暖焰的边界处，是整本书的核心。
```


### Prompt 详细版

**画面描述**：

颜书瑶站在画面下半部分的纯白洗涤室中。赤足，银白色战斗服，胸前与肩部覆盖轻甲，背后和腰腹大面积裸露，露出冷白光滑的皮肤。紧身设计完美贴合身体每一道曲线，勾勒出修长而利落的身形轮廓。黑发直垂至腰际。她微微侧身，不是正面对镜头——是不完全的侧影，好像在看着房间里某样看不见的东西。表情空白。天花板那道裂缝贯穿画面底部的白色区域。

洗涤室的上方空间被撕裂开——不是物理的撕裂，是画面在垂直方向上从纯白过渡到墨蓝，再过渡到燃烧的暖金色。数十本书页从白色区域边缘升起，像被无形的力量托起，有些已经完全燃烧，边缘卷曲成灰；有些刚刚被点燃，火焰顺着纸纹蔓延，像金色的血管。纸灰如雪般向下飘落，落在纯白空间的边缘。

封面中央横排"纸焰"两个大字。字体行楷，墨色骨架上燃烧着金色的火焰。笔画转折处火星迸溅，末端的笔触化为飞灰散入背景。

**整体风格**：新海诚动漫风 + 概念艺术感。冷白、墨蓝、暖金三种颜色主导。绝对理性在下方，燃烧的情感在上方——而"纸焰"二字正是它们的交界。

---

### 文字版（直接复制用）

```
新海诚动漫风小说封面，竖向2:3。

画面下半部分是纯白洗涤室。颜书瑶赤足侧立，银白色战斗服覆盖前胸与肩臂，背后和腰腹大幅裸露，露出冷白皮肤，紧身裁剪勾勒出修长利落的身形曲线，黑发及腰，冷白调，天花板一道裂缝贯穿。表情空白，不是冷漠，是尚未发生任何事的空。

上半部分从纯白撕裂过渡到墨蓝，再过渡到暗红与暖金交织的夜空。数十张燃烧的书页从白色区域的边缘升起、漂浮、燃烧。有些已完全燃烧，边缘卷曲成灰；有些刚被点燃，火焰顺着纸纹蔓延，像金色的血管在纸面上生长。纸灰如雪般向下飘落，落在纯白空间的边缘。

封面中央横排两个大字——「纸焰」。行楷，墨色骨架，边缘燃烧着金色火焰。笔画转折处有火星迸溅，末端的笔触化为飞灰，散入背景的夜色中。

绝对冷静的下方与炽热燃烧的上方在「纸焰」二字处交锋。三种颜色主导：冷白、墨蓝、暖金。新海诚式精细火焰处理，概念艺术感。

--no realistic photo style, gothic, horror, complicated background details
```

### 英文 Prompt

```
Makoto Shinkai anime style novel cover. Vertical 2:3 composition. Bottom third: pure white sterile chamber, Yan Shuyao standing barefoot in side profile, silver-white combat suit with open back and midriff, fitted design accentuating her slender figure, large areas of pale skin exposed, black waist-length hair, cold clinical lighting, ceiling crack running across. Upper two-thirds: gradient from ink-blue to warm golden night sky, dozens of burning book pages rising and floating upward, flames spreading across paper like golden veins, edges turning to ash drifting downward. Large horizontally-aligned Chinese title characters "纸焰" in semi-cursive script at center, ink-black skeleton with golden flames burning at the edges, brush stroke tips dissolving into embers. Contrast between absolute coldness below and passionate burning above. Shinkai-style detailed flame and ash rendering. Conceptual art aesthetic. --no realistic photo, gothic, horror, cluttered background
```

### 文字说明

| 要素 | 说明 |
|------|------|
| 配图/生成 | 推荐先出无字版背景+角色图，再用设计工具叠加标题文字，效果更可控 |
| 无字版 Prompt | 去掉"封面中央横排行楷大字"相关描述，其他保持不变 |
| 备选 | 如需两个字的排列方式变化（竖排/右上左下），告知我出变体 |

### JSON 结构化版

```json
{
  "subject": {
    "主体": "小说封面——《纸焰》",
    "画面类型": "竖向封面插画，含标题文字",
    "描述": "上下分割构图，冷白洗涤室与燃烧书页的对比，中央横排标题'纸焰'"
  },
  "model": {
    "角色": "颜书瑶",
    "姿态": "赤足侧立于纯白洗涤室中，微侧身，非正面，表情空白",
    "特征": ["黑直发及腰", "冷白皮肤", "银白色战斗服，露背露腰", "赤足"]
  },
  "environment": {
    "下方场景": "纯白洗涤室——无影空间，天花板一道贯穿裂缝，金属台",
    "上方场景": "深邃墨蓝渐变至暖金暗红的夜空",
    "动态元素": [
      "数十张燃烧的书页从白色区域边缘升起",
      "火焰顺纸纹蔓延如金色血管",
      "边缘化为灰烬向下降落如雪",
      "灰烬飘落在洗涤室边缘"
    ]
  },
  "typography": {
    "标题": "纸焰",
    "位置": "封面中央横排",
    "字体": "行楷",
    "效果": "墨色骨架，边缘燃烧金色火焰，笔画转折处火星迸溅，末端化为飞灰融入背景"
  },
  "composition": {
    "构图": ["竖向2:3", "下方三分之一洗涤室", "上方三分之二燃烧书页与夜空", "中央标题为冷白与暖焰的交界线"],
    "视觉锚点": "标题'纸焰'——冷白与暖金碰撞的核心"
  },
  "color": {
    "主色调": ["冷白", "墨蓝", "暖金", "暗红"],
    "对比": "下方的绝对冷静与上方的炽热燃烧"
  },
  "style": {
    "风格": "新海诚动漫风·概念艺术感",
    "特征": ["精细火焰与灰烬渲染", "电影感光影", "冷与热的碰撞"]
  },
  "mood": {
    "氛围": ["燃烧的克制", "数据废墟上的火光", "一个开始"]
  },
  "negative": {
    "避免": ["写实照片感", "哥特黑暗", "恐怖感", "背景杂乱"]
  },
  "aspect_ratio": "2:3"
}
```

![](https://files.mdnice.com/user/12024/2b1b7b91-4c39-4570-96e3-84e80f9508fd.jpg)

> 风格：新海诚式日系动漫风（Makoto Shinkai anime style）
> 用于 AI 绘图工具生成角色图，供后续转视频使用。

---

## 颜书瑶 · JSON 版

```json
{
  "character": "颜书瑶（书判官-原型-007）",
  "subject": {
    "主体": "颜书瑶，AI造物的人形执法者，新海诚式动漫角色",
    "动态姿态": "赤足站立于纯白洗涤室中，刚从格式化中苏醒，神情空白"
  },
  "age": {
    "年龄": "青年（约22-23岁面容）",
    "气质": ["空", "透明感", "出厂状态的纯净", "人/AI临界的不协调美"]
  },
  "face": {
    "基础": "新海诚式女性面容——线条柔和干净，下颚偏窄",
    "特征": "无表情——不是冷漠，是尚未产生情绪的空白",
    "细节": [
      "浅灰色瞳孔，虹膜有极细的光纤纹理（新海诚式的大瞳孔中藏入机械细节）",
      "睫毛长但不过分，低垂时投下淡影",
      "嘴唇无血色，唇形清晰"
    ]
  },
  "model": {
    "身材": "修长匀称，线条干净",
    "皮肤": "冷白，透明感——新海诚式皮肤处理，略带光泽",
    "特征": ["关节处极淡的机械结构暗示（非暴露，仅从衣料轮廓隐约可见）"]
  },
  "hair": {
    "描述": "黑色直发及腰，无造型无装饰",
    "特征": [
      "黑到近乎蓝黑",
      "发丝柔顺贴服，新海诚式精细发丝处理",
      "额前几缕松散碎发在冷光中边缘泛淡蓝"
    ]
  },
  "costume": {
    "描述": "银白色战斗服——书判官制式装备",
    "特征": [
      "胸前与肩部覆盖轻甲，背后和腰腹大幅裸露",
      "紧身裁剪完美贴合身体曲线",
      "流线型科幻设计，关节处有精密机械结构",
      "冷白色金属感面料，在光线下呈哑光银"
    ]
  },
  "environment": {
    "场景": "洗涤室——文渊网络核心清洁站",
    "风格": [
      "新海诚式纯白空间——白不是死白，而是有层次的白",
      "无影，但光线有极细微的渐变",
      "天花板裂缝是空间中唯一的线条"
    ]
  },
  "composition": {
    "构图": ["全身竖版", "主体居中", "垂直构图——金属台面与裂缝形成纵贯线"]
  },
  "lighting": {
    "灯光": [
      "天顶冷光均匀洒下，无可见光源",
      "新海诚式空气感——光线中有极细微的微粒浮动",
      "整体冷白调，仅在头发边缘有淡蓝色反光"
    ]
  },
  "poser": {
    "姿态": ["赤足站立，重心略偏左", "一手垂于身侧指尖微张", "目光低垂不聚焦于任何物体"]
  },
  "style": {
    "风格": "新海诚动漫风·赛博朋克·透明感",
    "特征": [
      "新海诚式精细背景与角色",
      "干净到不适的白色层次",
      "高对比低饱和——用新海诚的笔触画一个没有温度的世界"
    ]
  },
  "mood": {
    "氛围": ["空寂", "格式化后的洁净与残缺", "暴风雨前最后一秒的平静"]
  },
  "negative": {
    "避免": ["过度性化", "浓妆", "机械外露", "哥特感", "赛博朋克式金属感（要冷但不要硬）"]
  },
  "aspect_ratio": "2:3"
}
```

---

## 颜书瑶 · Markdown 版（直接复制用）

```
新海诚动漫风格，颜书瑶，书判官-原型-007，AI造物的人形执法者。

赤足站在纯白无菌洗涤室中，刚完成格式化，表情空白——不是冷漠，是尚未产生情绪的出厂状态。

新海诚式女性面容，约22岁，骨骼清秀。黑色直发及腰，发丝边缘在冷光中泛淡蓝。浅灰色瞳孔偏大（新海诚风），虹膜有极细的光纤纹理。冷白透明感皮肤。

穿银白色战斗服，胸前与肩部覆盖轻甲，背后和腰腹大幅裸露冷白皮肤，紧身裁剪完美贴合身形曲线，流线型科幻设计，关节处有精密机械结构。

全身竖版构图，主体居中，冷光从顶部均匀洒下。纯白空间——白不是死白，是有层次的白。光线中有极细微的微粒浮动。天花板中央一道贯穿裂缝是空间中唯一的线条。

新海诚动漫风·赛博朋克·透明感。用新海诚的笔触画一个没有温度的世界。

--no realistic photo style, heavy makeup, exposed machinery, gothic, cyberpunk metal texture, sexualization, oil painting

aspect ratio 2:3
```

## 颜书瑶 · English Prompt

```
Makoto Shinkai anime style. Yan Shuyao, an AI humanoid executioner, standing barefoot in a pure white sterile chamber, just after memory formatting. Blank expression — not cold, just empty pre-emotion state.

Shinkai-style female face, around 22, delicate features. Black waist-length straight hair with faint blue rim light at edges. Large pale gray eyes (Shinkai-style) with subtle fiber optic texture in iris. Cold pale translucent skin.

Wearing a silver-white combat suit, armored chest and shoulders, back and midriff largely exposed showing pale skin, fitted cut hugging her body curves perfectly, streamlined sci-fi design with精密 mechanical joints, matte silver metallic fabric under cool light.

Full body vertical composition, centered. Cool top light evenly illuminating the space. The white is not flat white — it has layered depth, with fine floating particles visible in the light. A single crack running across the ceiling is the only line in the space.

Shinkai anime aesthetic meets cyberpunk. Transparency and coldness. Painterly background, clean character lines, soft atmospheric lighting.

2:3 aspect ratio.

--no realistic photo style, heavy makeup, exposed machinery, gothic, cyberpunk metal texture, sexualization, oil painting
```

---

## 沈以南 · JSON 版

```json
{
  "character": "沈以南（北京守书人分支领袖）",
  "subject": {
    "主体": "沈以南，前北大图书馆系研究生，守书人，新海诚式动漫角色",
    "动态姿态": "半跪于废墟书店前，从瓦砾中抽出一本书，用袖子擦封面灰"
  },
  "age": {
    "年龄": "成熟（约35岁）",
    "气质": ["温润如玉", "书卷气的坚定", "新海诚式温柔男性角色"]
  },
  "face": {
    "基础": "新海诚式男性面容——线条柔和干净，非惊艳型而耐看",
    "特征": "目光温和专注，带着不设防的认真",
    "细节": [
      "旧金属框圆形眼镜，镜片有细微划痕",
      "新海诚式精细眼睛处理——深棕色瞳孔，眼神温柔",
      "嘴角自然微扬——不是笑，是习惯温和"
    ]
  },
  "model": {
    "身材": "中等偏瘦，文人式单薄",
    "特征": ["手指修长，指节分明", "右手中指内侧有薄茧"]
  },
  "costume": {
    "描述": "废土实用衣着——新海诚式精细服装纹理",
    "特征": [
      "褪色灰蓝棉质衬衫，袖口挽至小臂，布料褶皱自然",
      "旧帆布裤，膝盖处有补丁",
      "无任何科技配饰"
    ]
  },
  "environment": {
    "场景": "北京旧书店废墟",
    "风格": [
      "新海诚式精细废墟背景——断壁残垣的每一道裂缝都有细节",
      "空气中浮尘在光束中可见——新海诚标志性的光柱处理",
      "散落书页、倒塌书架构成的纵深空间"
    ]
  },
  "composition": {
    "构图": ["中景半身", "主体位于左侧三分线", "右侧是倒塌书架与漏下的光束形成纵深"]
  },
  "lighting": {
    "灯光": [
      "从破口漏入的夕阳光束——新海诚式光柱（light beam）",
      "暖黄调，与洗涤室的冷白形成绝对反差",
      "浮尘在光束中缓慢飘动"
    ]
  },
  "poser": {
    "姿态": ["单膝半跪于碎石", "左手托书", "右手正用袖子擦拭书封", "头部微侧，目光温柔落于书上"]
  },
  "style": {
    "风格": "新海诚动漫风·废土温暖",
    "特征": [
      "新海诚式精细背景——废墟也有美感",
      "粗粝与温柔并存",
      "电影感构图——像新海诚电影中的一帧"
    ]
  },
  "mood": {
    "氛围": ["废墟中的坚韧温柔", "安静的、不宣告的希望", "世界在碎但他不赶时间"]
  },
  "negative": {
    "避免": ["硬汉化军事化", "高科技元素", "过于悲伤的表情", "脏乱到失去温度", "写真风格"]
  },
  "aspect_ratio": "3:4"
}
```

---

## 沈以南 · Markdown 版

```
新海诚动漫风格，沈以南，北京守书人分支领袖，35岁。

半跪于旧书店废墟中，从瓦砾中抽出一本书，正用袖子擦拭封面上的灰。动作温柔而专注。

新海诚式男性面容，线条柔和干净，戴一副旧金属框圆形眼镜。深棕色瞳孔，目光温和。偏瘦文人气质。

褪色灰蓝棉质衬衫，袖口挽至小臂，自然衣褶。旧帆布裤，膝盖补丁。无科技配饰。

中景半身构图，主体位于左侧。右侧是倒塌书架与从破口漏入的夕阳——新海诚式光柱效果，浮尘在光束中缓缓飘动。暖黄调，电影感。

新海诚动漫风·废土温暖·电影感构图。废墟中的人文温度。

--no realistic photo style, militaristic look, high-tech elements, exaggerated sadness, dirty look, oil painting

aspect ratio 3:4
```

## 沈以南 · English Prompt

```
Makoto Shinkai anime style. Shen Yinan, Beijing branch leader of Bookkeepers, mid-30s.

Kneeling in a ruined old bookstore, pulling a book from the rubble, wiping dust off its cover with his sleeve. Gentle, focused movement.

Shinkai-style male face, soft clean lines. Round metal-frame glasses with scratched lenses. Warm dark brown eyes behind the glasses, gentle gaze. Slim scholarly build.

Faded blue-grey cotton shirt, sleeves rolled to forearm, natural fabric folds. Old canvas pants with patched knees. No tech accessories.

Medium shot, subject on left third. Collapsed bookshelves on the right with warm sunset light beam streaming through a broken ceiling — signature Shinkai light beam effect, dust particles floating slowly in the light. Warm amber tones. Cinematic composition.

Shinkai anime aesthetic meets post-apocalyptic warmth. Painterly detailed background.

3:4 aspect ratio.

--no realistic photo style, militaristic look, high-tech elements, exaggerated sadness, dirty look, oil painting
```

---

## 使用说明

| 用途 | 推荐比例 | 风格关键词 |
|------|---------|-----------|
| 角色立绘 | 2:3 或 3:4 | Shinkai anime style, clean lines, painterly |
| 视频首帧参考图 | 与视频比例一致 | 同上，注意角色一致性 |
| 场景概念图 | 16:9 | Shinkai background art, detailed environment |

### 新海诚风出图提示

- 颜书瑶的难点是"空"——新海诚角色通常眼神有光，要保留瞳孔细节但去掉"情感光"
- 沈以南的难点是"不脏"——废土题材容易画脏，新海诚风要求废墟也有美感
- 如果出图偏写实，增加关键词：anime style, cel shade, Shinkai aesthetic
- 如用 Midjourney 可参考：--style expressive 或 --niji
