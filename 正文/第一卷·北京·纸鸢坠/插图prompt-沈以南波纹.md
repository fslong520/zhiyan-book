# 第四章 · 沈以南「波纹」大招插画 Prompt

**场景定位**：沈以南首次展露"法师"能力——以指尖触地，释放千年纸魂频率的精神冲击波。

---

## 一、English Prompt（Midjourney / Niji 用）

```
Makoto Shinkai anime style, cinematic wide shot 16:9. A dramatic climax scene in a collapsed shopping mall ruins at dusk.

Shen Yinan, a 35-year-old scholarly man in faded blue-grey cotton shirt with rolled sleeves and round metal-frame glasses, is half-kneeling on the rubble-strewn concrete floor. His right index and middle fingertips press against the ground, eyes closed, head slightly bowed in intense concentration. Sweat on his forehead.

A visible transparent shockwave ripple expands outward from his fingertips in a perfect ring, distorting the air like heat haze. Within the ripple, ink-black Chinese calligraphy characters emerge and disperse like living spirits — poetic lines from an ancient text materializing in mid-air before dissolving into the wave: "纸" "上" "春" "秋" "墨" "中" "魂" "魄" — ink strokes floating like ghostly scripture.

Two dome-protocol mechanical dogs in mid-ground are caught in the wave's path. Their optical sensors flicker rapidly between red and blue lock-on lights, confused and overloaded. Dust particles suspended in the beam of fading dusk light from a broken ceiling above freeze mid-air. Small rubble pieces shift silently outward from the impact center.

In the background on the rubble pile: a young woman (Yan Shuyao) lies on her stomach, watching him with wide eyes. A bleeding teenage boy (Douzi) crouches nearby, also frozen in place. Both are illuminated by the warm ghostly glow of the calligraphy characters within the ripple.

The ripple is a soft translucent gold-white with ink-black brushstroke particles swirling within it — like the accumulated soul of a thousand years of literature being released in a single burst. Warm amber dusk light from above mixing with the cool spiritual glow of the wave. Epic, spiritual, melancholic yet triumphant.

New海诚 signature light beam through ceiling crack, atmospheric dust particles, painterly detailed ruins with moss and cracked concrete. Makoto Shinkai aesthetic, cel shaded, anime keyframe quality, —ar 16:9 —style expressive --niji 6

--no realistic photo, oil painting, horror, gore, excessive机械 detail, cluttered composition
```

---

## 二、JSON 结构化版（嵌入章节注释）

```json
{
  "tone": "燃·觉醒·精神能量的爆发——守书人以纸页为武器的终极姿态",
  "subject": "沈以南以指尖触地，释放千年纸魂频率的精神波纹——两台机械犬被过载定住",
  "moment": "诗号念毕、波纹刚刚展开的瞬间——碎石平移、灰尘凝固、机械犬瞳孔红蓝交替闪烁",
  "poem": "纸上春秋，墨中魂魄。千年一叩，荡尽虚妄。",
  "characters": [
    {
      "id": "沈以南",
      "age": "35岁",
      "face": "闭目，眉头微蹙，全神贯注——额头汗珠，下颌绷紧",
      "pose": "半跪，右手中指与食指指尖触地，左手自然垂于膝侧，头部微低",
      "hair": "短发，被汗粘在额角",
      "costume": "褪色灰蓝棉衬衫，袖口挽至小臂，自然衣褶，旧帆布裤——与前期角色设定一致"
    },
    {
      "id": "颜书瑶（她）",
      "age": "22岁",
      "face": "趴在地上仰视——瞳孔放大，表情不是恐惧，是一种从未见过的震撼",
      "pose": "俯卧于碎石堆上，一手撑地微微抬起上半身",
      "costume": "旧外套，衣上有灰和血迹"
    },
    {
      "id": "豆子",
      "age": "18岁",
      "face": "侧脸，嘴微张，同样被定住",
      "pose": "蹲/伏在矮墙边，一手按着流血的手臂",
      "costume": "旧外套肩部有补丁"
    }
  ],
  "environment": {
    "场景": "坍塌商场废墟空地，黄昏",
    "细节": [
      "地面碎混凝土与裸露钢筋",
      "断裂的混凝土柱",
      "天花板破口漏入一束夕阳光——新海诚式光柱",
      "波纹过处碎石无声平移",
      "灰尘在半空凝固"
    ]
  },
  "lighting": {
    "光源": "上方破口漏入的黄昏日光 + 波纹自带的暖白萤光",
    "色温": "暖黄（日光）与暖白（波纹）交织",
    "特征": "波纹呈半透明暖金色，像一圈扩散的光晕；日光从破口斜射，光束中浮尘可见"
  },
  "dynamics": "波纹正以手指触地点为中心向外扩散——空气中可见透明涟漪，碎石在地面平移，灰尘颗粒被冲击波推成环状波纹",
  "composition": {
    "镜头": "全景/宽幅——16:9电影感构图",
    "焦点": "沈以南指尖触地点——波纹的源心",
    "纵深": "前景沈以南半跪（左下黄金分割点），中景两侧机械犬瞳孔闪烁，远景颜书瑶与豆子伏于碎石上，背景是倒塌的商场结构与黄昏天空"
  },
  "color": {
    "主色": "灰褐（废墟）、暖黄（日光）",
    "辅色": "墨黑（诗号文字）、暖白（波纹光晕）",
    "对比": "冷灰废墟与暖金波纹的碰撞——精神能量在物质废墟中点亮",
    "倾向": "暖——悲壮但充满力量的暖"
  },
  "calligraphy": {
    "描述": "波纹中以墨黑色书法笔画浮现诗号字符——'纸''上''春''秋''墨''中''魂''魄'等字在涟漪中若隐若现，如千年纸魂具象化——笔画边缘半透明，像墨水在水中弥散",
    "风格": "行楷，墨色浓淡不均，有飞白效果——不是印刷体，是手写墨迹的精神投影"
  },
  "style": {
    "风格": "新海诚动漫风·魔幻现实主义",
    "特征": [
      "新海诚式精细废墟背景",
      "光柱与浮尘",
      "透明波纹中的水墨书法视觉",
      "电影感宽幅构图——关键帧级画面"
    ]
  },
  "mood": ["千年积累一瞬释放", "文人的绝地反击", "书的灵魂在燃烧"],
  "negative": ["写实照片感", "恐怖感", "过度的赛博机械风", "脏乱到失去美感", "血腥", "画面杂乱角色过多"],
  "aspect_ratio": "16:9"
}
```

---

## 三、中文纯文本版（直接复制用）

```
新海诚动漫风·魔幻现实主义，16:9宽幅电影感构图。

坍塌商场废墟空地，黄昏。一束夕阳从天花板破口斜射而下，光束中浮尘翻滚。

沈以南半跪于碎石地面上。灰蓝色旧衬衫，袖口挽至小臂，旧金属框圆眼镜。右手中指与食指指尖触地，闭目，额头汗珠。他以指尖为媒介，将自己从千年纸页中积累的精神频率一次性向外释放。

一道肉眼可见的透明波纹从他指尖扩散开来——暖金色半透明涟漪，像一口沉埋千年的古钟被撞响时发出的光。波纹内部有墨黑色的书法笔画在流转——「纸」「上」「春」「秋」「墨」「中」「魂」「魄」等字在涟漪中若隐若现，如千年纸魂具象化，笔画边缘弥散如墨水入水。

波纹过处：碎石无声平移，灰尘在半空凝固。两台穹顶协议机械犬定在中景处，瞳孔锁定灯在红色与蓝色之间疯狂闪烁——传感器被千年书魂的频率冲击过载。

远景：颜书瑶俯卧于碎石堆上，撑起上半身，瞳孔放大，看着这一切。豆子蹲在矮墙边，手按着流血的手臂，也被定格在这一瞬。

暖黄夕阳与暖白波纹交织。废墟的冷灰与墨色书法的碰撞。千年纸上春秋，一叩荡尽虚妄。

新海诚式精细废墟背景，丁达尔光柱，浮尘粒子，透明涟漪中的水墨书法视觉，悲壮而充满力量的觉醒时刻。

--no realistic photo, oil painting, horror, gore, excessive cyberpunk, cluttered composition

aspect ratio 16:9
```
