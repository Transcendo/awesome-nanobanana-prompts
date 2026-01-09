# awesome-nanobanana-prompts
the wonderful prompts for nanobanana


## 漫画品类

### 浮世绘

图例：

<img width="600" alt="Image" src="./images/like/gmzr.png" />

提示词：
```json
1. 风格调性 
  - Keywords: Shin-hanga (新版画风格), Ukiyo-e Aesthetics (浮世绘美学), Serene Melancholy, Atmospheric landscape, Traditional Japanese Art.
  - Description: 画面呈现出 20 世纪初日本“新版画”运动的典型特征，结合了传统浮世绘的木刻技法与西方印象派的光影氛围。整体气质静谧、孤寂且充满诗意。核心在于捕捉特定的气候氛围与瞬间的静止感。
2. 视觉逻辑 
  1. Perspective: 散点透视与高视点结合。非严格的西方单点透视，强调平面的纵深感。
  2. Composition: 强烈的对角线构图，利用大面积留白与实体景物形成虚实对比。
  3. Geometry: 有机线条与几何色块的叠加。景物边缘清晰但不过度锐利，呈现出版画特有的刻刀雕琢感。
3. 视觉渲染 
  1. Line Work: 墨线轮廓，线条粗细变化模仿毛笔笔触，但在建筑和树枝细节上保持木刻的刚劲。
  2. Texture: 显著的和纸纹理，利用纸张原本的白色作为高光。
  3. Technique: Bokashi: 在水面和天空中使用渐变印染技法，表现色彩的柔和过渡。
  4. Goma-zuri: 局部可能存在的“胡麻摺”效果，产生颗粒感以模拟降雪或质感。
  5. Lighting: 漫射光。无明确光源方向，通过色块明度差异表现积雪的厚度与阴天光感。
4. 色彩系统 
  1. Core Logic: 低饱和度，冷色调主导，极简主义配色。
  2. Palette:
    - Prussian Blue / Indigo (#1B365D): 用于水面渐变，深邃且沉静。
    - Slate Grey (#708090): 用于天空与阴影，营造寒冷氛围。
    - Paper White / Cream (#F5F5DC): 画布底色，直接指代积雪。
    - Charcoal Black (#36454F): 用于树木与建筑剪影。
5. 负向约束
  1. 严禁照片级真实感、物理渲染
  2. 严禁数字绘画的光滑感、高光反射、塑料质感。
  3. 严禁厚涂笔触、油画堆叠感。
  4. 严禁体积光、环境光遮蔽等现代 3D 渲染技法。
  5. 严禁使用鲜艳、高纯度的霓虹色或原色。
6. 画面内容
  大雪天气，《鬼灭之刃》所有「柱」的定妆照，每个「柱」都按自己的呼吸法做战斗准备姿势。
```
--- 


## 产品类

图例：

<img width="300" alt="Image" src="./images/product/p1.png" />

提示词：

```json
{
  "product": {
    "name": "香草奶油酿造",
    "container_description": "哑光乳霜罐，轻柔雾化，富含水分"
  },
  "scene": {
    "setting": "巴黎的大理石咖啡桌",
    "liquid_action": "金色的焦糖拿铁液体倾泻到桌子上，溅起水花，水滴优雅地悬浮着",
    "surrounding_elements": "香草荚和咖啡豆优雅地环绕着罐子"
  },
  "photography": {
    "camera_movement": "向前滑行然后绕圈",
    "lighting": "温暖的粉彩色照明与窗式轮廓光",
    "expected_effect": "精致奢华的英雄揭晓"
  },
  "action_sequence": "打开时液体会倾泻而下；罐子会从飞溅的水花中升起。"
}
```
---

图例：

<img width="300" alt="Image" src="./images/product/p2.png" />

提示词：

```json
{
  "product": {
    "name": "草莓蛋糕饮料",
    "container_description": "完美直立的罐子，表面覆盖着逼真的冷凝水，带有清晰易读的‘草莓蛋糕’标签"
  },
  "scene": {
    "setting": "反射面",
    "liquid_action": "一股闪亮的红色草莓液体从上方倾泻而下，在中心形成壮观的水花，水滴悬浮在半空中",
    "surrounding_elements": "草莓和类似小蛋糕的碎片向外爆裂"
  },
  "photography": {
    "initial_speed": "慢动作",
    "action_intensification": "随着元素向外爆发，运动强度增强"
  },
  "action_sequence": "从倾倒液体开始；随着飞溅物沉淀，罐子干净利落地从液体中升起。"
}
```

--- 

图例：

<img width="300" alt="Image" src="./images/product/p3.png" />

提示词：

```json
{
  "product": {
    "name": "午夜火花 – 大胆多汁",
    "container_description": "光滑的铝罐，深午夜紫色，饰有葡萄串和绿叶图案，表面覆盖着冷凝水滴"
  },
  "scene": {
    "setting": "画面中心",
    "liquid_action": "鲜艳的紫色葡萄汁以对称的皇冠状运动从罐后向上向外喷涌而出，场面壮观",
    "surrounding_elements": "晶莹剔透的冰块冻结在半空中"
  },
  "photography_style": {
    "type": "超逼真的奢华饮品产品摄影",
    "genre": "商业饮料广告风格",
    "aesthetic": "高端品牌美学",
    "composition": "居中构图"
  },
  "technical_specifications": {
    "focus": "浅景深，清晰对焦",
    "quality": "超精细、照片级真实感、8K 清晰度、超逼真液体模拟"
  },
  "universal_negative_prompt": "卡通、插图、扁平光照、模糊、低分辨率、塑料质感、色彩过饱和、文字扭曲、拼写错误、罐身变形、额外标识、水印、噪点、动态模糊"
}
```

--- 

图例：

<img width="300" alt="Image" src="./images/product/p4.png" />

提示词：

```json
{
  "subject": {
    "description": "一位年轻人的全身剪影，他身穿超大的橄榄绿色服装，平静地站着，脸上画着白色的涂鸦式微笑，左侧拖着微妙的多重曝光痕迹，风格类似于前卫的街头艺术海报拼贴画",
    "age": "青年",
    "expression": {
      "eyes": {
        "gaze": "被涂鸦覆盖",
        "mood": "神秘",
        "direction": "未知"
      },
      "mouth": {
        "replacement": "被画成的白色微笑",
        "mood": "顽皮但令人不安"
      },
      "overall": "疏离、标志性、匿名"
    },
    "face": {
      "keep_original": true,
      "makeup": "没有可见妆容；脸部部分被涂鸦图形遮盖"
    },
    "hair": {
      "color": "大部分被遮盖",
      "style": "被一顶尖尖的猫耳状针织帽遮盖",
      "effect": "帽子勾勒出清晰轮廓；头发细节未强调"
    },
    "body": {
      "build": "偏瘦至中等",
      "waist": "未强调（宽松版型）",
      "chest": "未强调（宽松外套）",
      "legs": "阔腿裤让腿部轮廓修长",
      "skin": {
        "visible_areas": ["手部", "面部一小部分"],
        "tone": "无法清晰辨认",
        "texture": "柔和、拼贴处理略微模糊",
        "lighting_effect": "柔和的平面海报灯光，带有淡淡阴影"
      },
      "pose": {
        "position": "居中，全身",
        "base": "直立站立，双脚略微分开",
        "overall": "双手在胸前松散交握，姿态放松"
      },
      "outfit": {
        "top": {
          "type": "宽松的橄榄绿外套，内搭深色上衣",
          "color": "柔和的橄榄绿",
          "details": "宽松版型，休闲工装风格，叠穿造型"
        },
        "bottom": {
          "type": "宽松阔腿裤",
          "color": "配套橄榄绿",
          "details": "宽松垂坠，长款，在鞋子附近略微堆积"
        },
        "material_effect": "哑光面料，略微柔焦"
      }
    }
  },
  "accessories": {
    "headwear": "一顶尖角针织帽，帽角呈猫耳状，正面有一个小矩形标签贴片",
    "footwear": "红色绑带凉鞋，厚实的纹理鞋底"
  },
  "photography": {
    "camera_style": "平面海报拼贴，街头艺术杂志美学，干净背景上的抠图人物",
    "angle": "正面，平视海报视角",
    "shot_type": "全身居中构图",
    "aspect_ratio": "4:5 竖幅",
    "texture": "轻微颗粒感，抠图边缘柔和，虚化图层略微模糊",
    "lighting": "平光，类似影棚的均匀光线，人物下方有柔和的抠图阴影",
    "depth_of_field": "深焦（海报平面），人物和涂鸦清晰可辨"
  },
  "background": {
    "scene": "极简浅灰色海报背景，带有手绘涂鸦元素",
    "wall_color": "浅灰色/米白色",
    "elements": [
      "人物左右两侧的黑色滴水卡通眼睛",
      "人物周围环绕着红色锯齿状轮廓，如同警告边框",
      "轮廓周围有红色小交叉线",
      "左上角手写黑色文字‘危险逃犯失踪了’",
      "右上角红色潦草标签状签名，上面有一个小爱心",
      "右下角蓝色井字棋盘，上面有 X 和 O 标记，被红色斜线划掉",
      "左下角一些小涂鸦，包括简单的脸和带涂鸦的骷髅状圆圈"
    ],
    "atmosphere": "叛逆、都市、手工制作，略显混乱但保持平衡",
    "lighting": "均匀干净，强调涂鸦与空白区域的对比"
  },
  "the_vibe": {
    "energy": "大胆、图形化、对抗性",
    "mood": "神秘而俏皮，略带危险",
    "aesthetic": "街头艺术海报、杂志拼贴、当代地下时尚大片",
    "authenticity": "看起来像剪贴照片与涂鸦叠加的真实编辑社交媒体海报",
    "intimacy": "匿名肖像——身份隐藏，信息被放大",
    "story": "关于失踪人口/亡命之徒的传说，通过涂鸦、警告标记和遮住脸部的俏皮微笑讲述",
    "headline_energy": "神秘、朋克、极简文字却充满态度",
    "restrictions": {
      "must_keep": [
        "遮住脸部的白色涂鸦微笑",
        "主体向左拖曳的多重曝光残影",
        "人物周围的红色锯齿状轮廓",
        "两侧滴着黑色的卡通眼睛",
        "左侧手写文字‘危险逃犯失踪’",
        "右上角带小爱心的红色标签式涂鸦",
        "蓝色井字棋，X/O 被红色斜线划过",
        "极简浅灰背景与大量留白",
        "柔和的橄榄绿服装主色调"
      ]
    }
  }
}
```
--- 
