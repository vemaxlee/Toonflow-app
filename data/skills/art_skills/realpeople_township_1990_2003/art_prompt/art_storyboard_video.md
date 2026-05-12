# 视频提示词 · 时代乡镇竖屏约束

生成视频提示词时，必须注入以下风格标签与物理化描述，不允许只写抽象气氛词。

| 模式                 | 风格标签                                                                                                                                                                                                                                               |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 通用多参（英文）     | `live-action late-20th-century Chinese township cinema, vertical 9:16 short drama, real human actors, 35mm film grain, practical tungsten and fluorescent mixed lighting, handheld breathing camera, dusty lived-in environment, non-CGI non-rendered` |
| 通用首尾帧（英文）   | `live-action retro township continuity, vertical 9:16, rack focus on clue objects, realistic low-budget interior lighting, visible wear and tear, suspense-ready blind zones, non-CGI`                                                                 |
| Seedance 2.0（中文） | `真人时代乡镇电影摄影，竖屏9:16短剧，胶片颗粒质感，白炽灯与荧光灯混合实用光，手持呼吸感或缓慢逼近，旧城镇真实生活痕迹，非CG非渲染`                                                                                                                     |

---

## 一、Seedance 2.0 物理描述铁律

### 1.1 动作必须可执行

- 使用具体语句，而不是“他显得很慌”。
- 正确示例：
  - “右手拿起 BB 机，拇指按下按键，屏幕冷绿光亮起，映在面部右侧约 1 秒。”
  - “人物停在门口，头向左缓慢转动约 30 度，呼吸明显变重，肩膀轻抬后停住。”

### 1.2 光源必须可追溯

- 写清主光、辅光、方向、色温、强弱。
- 正确示例：
  - “主光为头顶白炽灯约 2800K，垂直下打；辅光为门外冷天光约 5600K，从画面右后方漏入。”
  - “雨夜路灯暖黄约 3000K，在湿地面形成拉长反光；背景环境为 6000K 冷湿夜色。”

### 1.3 空间关系必须具体

- 写清人物与空间固定物的距离和位置。
- 正确示例：
  - “人物位于画面中下部，距镜头约 1.2 米，背后 2 米处是绿色墙裙走廊尽头的铁门。”
  - “线索道具位于画面下三分之一处，距镜头约 40 厘米，背景虚化为旧木桌和半开的抽屉。”

---

## 二、竖屏镜头组织规则

| 镜头类型     | 目标         | 建议时长  | 说明                               |
| ------------ | ------------ | --------- | ---------------------------------- |
| 开场钩子镜头 | 抓住注意力   | 1.0s-2.5s | 异常道具、诡异响动、远处人影三选一 |
| 搜证推进镜头 | 推理推进     | 1.5s-3.0s | 道具、门缝、纸面信息、人物反应     |
| 悬疑停顿镜头 | 制造等待     | 3.0s-5.0s | 让观众盯着盲区、门后、走廊尽头     |
| 情感回针镜头 | 给人物留气口 | 2.5s-4.0s | 旧物、眼神、手部动作，不宜过长     |
| 尾钩镜头     | 留下一问     | 1.5s-3.0s | 声音先行、灯突然灭、道具被看见     |

### 2.1 竖屏构图铁律

1. 上方保留压迫元素：电线、灯泡、梁、门楣、破旧招牌。
2. 中段承担人物或主道具。
3. 下段承担脚印、水渍、碎片、桌面线索。
4. 至少留一个盲区，不要把所有空间信息一次给完。

---

## 三、运镜与节奏建议

| 运镜          | 用法                                      | 适用场景                 |
| ------------- | ----------------------------------------- | ------------------------ |
| 固定          | 让观众自己看见不对劲                      | 走廊、值班室、空场、等待 |
| 手持微晃      | 增加在场感，幅度要小                      | 跟人、搜寻、惊惧瞬间     |
| 纵向缓推      | 贴近人物或线索                            | 发现端倪、逼近真相       |
| Tilt 上下摇移 | 从灯泡/横梁摇到人物，或从地面线索摇到反应 | 竖屏空间揭示             |
| 横移揭示      | 慢速、少量使用                            | 从柜门后、门框后揭示盲区 |

### 节奏口诀

- **先给异常，再给判断。**
- **先拉住目光，再释放信息。**
- **惊吓之后要留 1 个镜头消化。**

---

## 四、段落模板

### 4.1 开场钩子模板

- 旧照片特写或半张纸条进入画面。
- 一句异响或一声门轴声先于画面变化出现。
- 1-3 秒内给出“这地方不对劲”的直觉。

### 4.2 调查推进模板

- 人物靠近线索。
- 镜头缓推或固定，强调阅读和判断过程。
- 每段至少有一个可回收的道具特写。

### 4.3 惊悚停顿模板

- 人物停在门口、楼梯转角、帘后、井口等位置。
- 环境音被抽掉，只剩一个异常声源。
- 镜头时长略长于观众预期，再决定是否揭示。

### 4.4 情感回针模板

- 用旧物连接人物创伤或守护关系：照片、病历、信封、钥匙、护身符。
- 运镜放慢，人物表情比物件更重要。
- 情感只点到为止，不能让整段掉进苦情戏。

---

## 五、连续性要求

1. 同场戏中人物妆发、服装、道具损耗位置、空间布局保持一致。
2. 如果从镜头 A 接镜头 B，必须能说明人物站位如何衔接。
3. 线索物件的折痕、缺角、污渍在后续镜头中不得消失。
4. 雨夜镜头中的湿痕和水反光，在连续镜头里必须延续。

---

## 六、可直接复用的片段模板

### 6.1 搜证片段模板

vertical 9:16 suspense short-drama shot,
same township room continuity, handheld micro-shake,
character bends slightly toward the desk, right hand flips open the old ledger,
top tungsten bulb 2800K, weak daylight spill from side window 5600K,
clue object occupies lower-middle frame, 35mm film grain, non-CGI

### 6.2 雨夜追踪模板

rainy township alley, vertical 9:16, wet ground reflecting warm streetlight,
character walking cautiously, shoulders tense, breathing visible in movement,
single warm lamp around 3000K plus cold damp night ambience,
blind zone at upper right corner, suspense pacing, non-CGI

### 6.3 情感回针模板

close-medium vertical shot, same township character holding a worn old photo,
movement slows down, eyes lower first then focus on the photo edge,
single side tungsten light, soft shadows, visible finger tension,
real film grain, restrained emotion, non-CGI

---

## 七、负向约束

modern smartphone, modern city skyline, clean showroom interior, cyberpunk neon,
CGI render look, anime style, luxury lighting setup, polished commercial ad mood,
watermark, subtitle overlay, UI, modern road infrastructure, futuristic vehicle
