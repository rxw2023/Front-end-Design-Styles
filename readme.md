# 前端设计主义展示 —— 50 种设计风格总览

> 参考 [UI UX Pro Max Skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) 通用风格列表扩充
---
> [国外地址](https://front-end-design-styles.1276430450.workers.dev/)
---
> [国内地址](https://oasis-fvwc.upma.site/)
---

## 1. 新粗野主义 (Neo-Brutalism)
- 明确的粗边框分割线 (border: 3px solid #111)
- 原始点阵网格背景 (radial-gradient 点阵)
- 大写等宽字体标签 (DM Mono, text-transform: uppercase)
- 卡片无圆角、直来直去的块状布局
- 实验编号系统 EXP. 01，强调"未完成/实验性"的粗粝感
- 硬阴影偏移 (box-shadow: 6px 6px 0 #111)

## 2. 瑞士/国际主义平面设计 (Swiss Style)
- 12 列网格系统 (grid-template-columns: repeat(12, 1fr))
- 非对称卡片布局（4 列 + 8 列交替，而非统一尺寸）
- 纯粹依赖排版层级（超粗 900 标题 + 等宽标签 + 正文）
- 克制色彩逻辑：--ink / --muted / --paper / --line 四色系统
- 目录式编排（Index / 2026.07）
- border-radius: 0，无任何装饰性元素

## 3. 日系编辑美学 (Japanese Editorial)
- 暖调纸色底 (#f1f0ea、#faf9f4) — 模拟纸张肌理
- Noto Sans SC + DM Mono 的中日文混排
- 极低对比度的柔和分割线 (#d4d3cc 暖灰)
- 标题后置荧光黄 (#dfff00) 下划线装饰，常见于日本杂志封面
- 低饱和暖色谱，仅荧光黄一处亮色点缀

## 4. 终端/开发者工具审美 (Terminal/CLI Aesthetic)
- 状态指示器 "Node online" + 绿色脉冲圆点 (animation: pulse)
- 全文 Monospace 信息层级 (DM Mono 用于所有元数据)
- 实验档案 (Experimental Archive) 品牌定位
- 冷工业感配色（墨黑 #0d0f0e + 灰绿 #c5d0c0 + 酸黄 #dfff00 + 深蓝 #2454ff）
- 命令行提示符 $ 和路径式文本表达

## 5. 玻璃拟态 + 复古未来主义 (Glassmorphism + Retrofuturism)
- 扫描线覆盖层 (repeating-linear-gradient + mix-blend-mode: overlay)
- 卡片采用模糊玻璃 (backdrop-filter: blur(16px))
- 酸黄 #dfff00 和深蓝 #2454ff 的高对比搭配，接近 80 年代电子/赛博美学
- 半透明边框 (border: 1px solid rgba(255,255,255,0.1))

## 6. 体素美学 (Voxel Aesthetic)
- 粗像素主义：image-rendering: pixelated / 0 圆角 / Press Start 2P 字体
- 立体凸起/凹陷边框 (inset 0 -4px 0 #2B2B2B 模拟方块阴影面)
- 游戏界面化：物品栏网格 + 石头按钮 + HP/经验条指示器
- 大地色限制色谱：草绿 #7B8F3A / 泥土棕 #8B6B3D / 石头灰 #6D6D6D / 橡木黄 #C4A87C
- 16×16 隐式网格系统（仿 chunk 渲染单位）
- 无抗锯齿、无阴影模糊、steps() 帧动画

## 7. 新拟物化 (Neumorphism)
- 柔和对向 box-shadow (8px 8px 16px 暗 + -8px -8px 16px 亮)
- 卡片与背景同色 (#e0e5ec)，仅靠光影区分层次
- 按下用 inset 内阴影模拟凹陷
- 大圆角 20px，低对比柔和灰蓝调

## 8. 复古 Windows 95 (Retro Win95)
- 经典 #008080 青绿色桌面背景
- 3D 凸起/凹陷边框（亮暗色 border 组合 + outset/inset）
- #c0c0c0 灰色窗口面板 + 线性渐变标题栏
- MS Sans Serif 系统字体 / 点状虚线 outline 聚焦框
- 任务栏 + Start 按钮的完整桌面模拟

## 9. 有机自然 (Biophilic Design)
- 大地色系：奶油米底 #f3f0e8 + 鼠尾草绿 #6b8a5e 点缀
- radial-gradient 光斑模拟透过树叶的光影
- 米白卡片 (#fdfbf5) 模拟手工纸触感
- 16px 大圆角，低对比度漫反射阴影
- header 底部 3px 绿色边框

---

## 10. 3D 超写实 (3D & Hyperrealism)
- perspective: 1000px 创建深度空间
- hover 时多轴变换：translateY(-15px) + translateZ(50px) + rotateX(5°) + rotateY(-3°)
- 多层 rgba 层叠阴影模拟真实光照
- 线性渐变卡片背景模拟玻璃/金属材质
- cubic-bezier(0.25,0.46,0.45,0.94) 缓动

## 11. 鲜艳块状 (Vibrant & Block-based)
- 高饱和撞色：红 #ff6b6b + 黄 #ffd93d
- 硬阴影偏移：box-shadow: 4px 8px 0 #111
- 3px solid 粗黑边框，零圆角
- 白色背景最大程度突出色彩张力

## 12. OLED 暗黑 (Dark Mode OLED)
- 纯黑底色 #000 利用 OLED 像素级黑色节能
- 极暗卡片 #0a0a0a 通过 1px #1a1a1a 边框微弱区分
- 白色 heading + 浅灰 body，远超 WCAG AA 对比度
- 反色按钮：白底黑字在暗色页面中形成视觉锚点

## 13. 无障碍伦理 (Accessible & Ethical)
- 严格遵循 WCAG AA/AAA (4.5:1 最低对比度)
- 2px solid #000 粗黑边框，元素边界清晰
- 推荐 Atkinson Hyperlegible 专为低视力设计字体
- 所有交互元素有 2px 可见 focus outline
- 最小 44x44px 触摸目标，兼容屏幕阅读器

## 14. 粘土风 (Claymorphism)
- 对向 box-shadow 创造柔软凸起 (8px 8px 16px / -8px -8px 16px)
- 卡片与背景同色 #f0c9a0，无边框仅靠光影
- 超大圆角 24px，像被揉圆的粘土块
- 按钮 active 用 inset 内阴影模拟按压凹陷
- 暖泥土色调：杏色 → 可可色

## 15. 极光界面 (Aurora UI)
- 深色背景叠加多个 radial-gradient 半透明光斑
- 蓝绿紫红多色交织，模拟北极光色彩流动
- backdrop-filter: blur(10px) 毛玻璃卡片
- 翡翠绿 #0d9488 按钮，柔和高级
- 1px rgba 白 0.08 微光边框

## 16. 复古未来 (Retro-Futurism)
- 太空深紫背景 #1a0a2e
- 霓虹粉 #ff6b9d 主题色，发光辉光阴影
- 半透明紫色卡片 rgba(40,20,60,0.8)
- 80 年代科幻标题风格
- 不同于 Cyberpunk 的冷硬，用粉紫带来温暖的科技怀旧

## 17. 扁平设计 (Flat Design)
- 零阴影 (box-shadow: none)，纯二维平面
- 鲜明品牌蓝 #3490dc
- 白色卡片 + 1px 浅灰边框
- 3-4px 紧凑圆角
- 无渐变无纹理，极快渲染速度

## 18. 液态玻璃 (Liquid Glass)
- 超强模糊 backdrop-filter: blur(20px)
- 深色渐变背景 (黑蓝 → 紫黑)
- 卡片仅 rgba(255,255,255,0.03) 几乎完全透明
- 16px 大圆角模拟液体表面张力
- 1px 微光边框，高级 SaaS 产品质感

## 19. 动效驱动 (Motion-Driven)
- 弹簧缓动 cubic-bezier(0.34,1.56,0.64,1) 弹性回弹
- hover 时 scale(1.05) + rotate(1deg)
- 暗色舞台：纯黑底突出动效变化
- hover 边框从灰变红，色彩成为动效信号
- 配合 prefers-reduced-motion 尊重用户偏好

## 20. 微交互 (Micro-interactions)
- 按钮 active scale(0.95) 按压缩放反馈
- 所有过渡 200-300ms Material Design 标准缓动
- 渐进阴影从 2px/0.04 → 8px/0.1
- 1px #eee 极浅边框精确视觉边界
- hover translateY(-2px) 轻微 Z 轴抬升

## 21. 包容性设计 (Inclusive Design)
- 2px solid #000 高对比粗边框
- 大号触摸目标 (padding: 0.7em 1.5em, 间距 ≥8px)
- 可见焦点导航 + 语义化 HTML
- 字号 ≥16px, 行高 1.6+
- 信息不单独依赖颜色传达

## 22. 零界面 (Zero Interface)
- 卡片透明 (background: transparent, border: none)
- 无 hover 反馈，无任何装饰性交互
- 按钮仅 1px #ccc 边框 + 透明背景
- 留白即层级——仅靠字号、字重、间距区分
- 适合语音助手/AI 对话界面

## 23. 柔和 UI 进化 (Soft UI Evolution)
- 多层精致阴影 (1px 边框 + 2px/12px 阴影)
- 极浅蓝灰底色 #eef0f4
- 蓝紫色按钮 #6382dc
- 14px 大圆角产生"软垫"触感
- 在 Neumorphism 与 Flat Design 间的企业级平衡

## 24. 新粗野 2.0 (Neubrutalism)
- 暖色奶油底 #fffaee 替代传统灰白
- 红 #ff6b6b + 黄 #ffd93d 撞色搭配
- box-shadow: 4px 4px 0 #000 不模糊硬阴影
- 3px solid #000 粗黑边框
- Gen Z 友好的乐观版粗野主义，Figma 社区热门

## 25. 便当盒网格 (Bento Box Grid)
- Apple 灰色调 #f5f5f7 底色
- 不等大圆角卡片 (18px) 像日式便当盒排列
- 20px 胶囊按钮 (pill-shaped)
- 无边框，仅靠微弱阴影和圆角定义边界
- 产品特性展示最佳方案

## 26. Y2K 美学 (Y2K Aesthetic)
- 冰蓝 (#d1f7ff) → 樱花粉 (#ffccde) 渐变背景
- 半透明磨砂卡片 (blur 5px)
- 粉红 #ff69b4 主色调，发光辉影
- 16px 胶囊圆角，千禧乐观未来感
- 复刻 2000 年代初 Flash/早期 iOS 审美

## 27. 赛博朋克 (Cyberpunk UI)
- 纯黑底 #0a0a0a + 霓虹品红 #ff00ff + 亮绿 #00ff88
- 发光边框 (box-shadow 0 0 10px neon)
- DM Mono 等宽字体 + 文字辉光 text-shadow
- 零圆角硬朗锐利
- 致敬《银翼杀手》《赛博朋克 2077》

## 28. AI 原生界面 (AI-Native UI)
- 蓝紫渐变 #667eea → #764ba2 (OpenAI 风格)
- 卡片带蓝紫色边框 + 微弱阴影
- 亮白底色 #fafbff，12px 流线型圆角
- 按钮 hover 时渐变加深
- 适合 AI SaaS 专业产品

## 29. 孟菲斯设计 (Memphis Design)
- 粉 #ff6b6b + 青 #4ecdc4 + 黄 #ffe66d 三色撞色
- 彩色硬阴影交替 (奇数青/偶数黑)
- 波点锯齿装饰性韵律
- 20px 胶囊大圆角按钮
- 1981 年米兰诞生，用童趣反叛现代主义

## 30. 蒸汽波 (Vaporwave)
- 深紫渐变 (深蓝 → 深紫)
- 霓虹粉紫文字 #e8a0ff + 青色 #00ffff
- 发光辉影模拟 CRT 色彩溢出
- 半透明深紫卡片层层穿透
- 80 年代合成波音乐美学 + 消费主义幻灭感

## 31. 维度层叠 (Dimensional Layering)
- 三层递进 box-shadow (1px/2px/4px/8px)
- 浅灰舞台 #f0f0f5，大卡片通过阴影深度建立 Z 轴
- 1px #eee 极浅边框 + 悬浮 hover
- 仪表盘和卡片布局的最佳方案

## 32. 极度极简 (Exaggerated Minimalism)
- h1 字号 5rem, 900 字重, -0.05em 间距
- 纯白背景，卡片仅顶部 1px #eee 细线
- 无 hover 反馈，拒绝多余交互
- 字体即设计——无色彩纹理阴影

## 33. 动态排版 (Kinetic Typography)
- 文字即 Hero——6rem+ 超大字重 900
- line-height: 0.9 紧凑行高制造冲击
- 黑底白字极端对比
- 影视级标题风格（电影海报/音乐节）

## 34. 视差叙事 (Parallax Storytelling)
- 多层纵向渐变 (暖米 → 浅棕 → 暖米)
- 半透明白色卡片叠加，背景透过可见
- 深棕 header + 古铜棕按钮
- 翻阅故事书的沉浸体验，品牌叙事最佳方案

## 35. 瑞士现代 2.0 (Swiss Modernism 2.0)
- 卡片仅用 2px 黑色顶部线分割 (border-top)
- h1 4rem 900 字重 0.85 行高
- 纯白底 #fcfcfc，零阴影零圆角
- 瑞士 1.0 的极端化——字体是唯一的材料

## 36. 科幻 HUD (HUD / Sci-Fi FUI)
- 深空蓝底 #001020 模拟太空飞船控制台
- 发光青色边框 (#00aaff) + 辉光 box-shadow
- DM Mono 等宽字体 + 科技蓝文字
- 透明按钮带青色 1px 边框，hover 时半透明底
- 致敬《钢铁侠》《星际迷航》FUI 传统

## 37. 便当网格 2.0 (Bento Grids 2.0)
- 暖灰底色 #f2f2f7
- iPhone 经典红 #ff3b30 点缀按钮
- 20px 大圆角，无边框无阴影(默认)
- grid-column/row span 实现不等大拼接
- 比 Apple Bento 更有温度和活力

## 38. 空间计算 (Spatial UI / VisionOS)
- backdrop-filter: blur(20px) 强模糊
- 22px 超大圆角接近 VisionOS 窗口
- 1px rgba 白 0.08 微光玻璃轮廓
- 深空蓝渐变背景 + 蓝紫半透明按钮
- 轻量化交互——界面不重，空间感轻

## 39. 电子墨水 (E-Ink / Paper)
- 暖白纸色 #faf8f0 模拟高质量纸张
- Georgia / 衬线字体，16px 1.8 行高
- 底部 1px #ddd8c8 细线分割
- 零阴影——纸质世界没有投影
- 致敬 Kindle 电子墨水阅读器

## 40. Z 世代混沌 (Gen Z Chaos / Maximalism)
- 黑底白字 header + 亮黄文字 + 橙红卡片
- 3px 3px 0 橙色硬阴影，彩色交替
- 2px solid #000 粗边框
- 30px 大胶囊橙色按钮
- 精心设计的"不完美"——Z 世代反叛宣言

## 41. 仿生有机 2.0 (Biomimetic / Organic 2.0)
- 淡绿灰 → 深绿灰纵向渐变模拟森林光线衰减
- 半透明白色卡片 (rgba 白 0.5) 像细胞壁
- 深绿 #2a4a2a header + 20px 有机圆角
- 鼠尾草绿按钮 (可持续/健康信号)
- 从自然结构和系统学习设计逻辑

## 42. 反精致粗糙 (Anti-Polish / Raw Aesthetic)
- 边框：border-style: dashed 虚线
- DM Mono 等宽字体打破专业字体规则
- 零圆角 + 零阴影 + 无 hover 反馈
- 白底纯文本，像线框图被直接推上线
- 刻意的不完美是对过度设计的反动

## 43. 触觉数字 (Tactile Digital / Deformable UI)
- 底部 2px 阴影模拟卡片物理厚度
- active 时 scale(0.98) 按压形变
- 暖灰底色 #f8f5f0 (像棉纸/亚麻布)
- 深棕按钮 (木质触感) + 10px 自然磨损圆角
- 让冰冷屏幕产生温暖触感

## 44. 自然精粹 (Nature Distilled)
- 奶油米底色 #f5f2eb (羊皮纸晨光色)
- 森林绿 header #5a6a4a (克制的自然)
- 极弱阴影 (0.03 不透明度)
- 暖白卡片通过色彩温度区分而非阴影
- 提炼自然为色彩和比例，不借用自然形态

## 45. 光标交互 (Interactive Cursor Design)
- cursor: crosshair 十字准星光标
- 深紫科技蓝底 #1a1a2e + 发光卡片微辉
- 1px rgba 白 0.05 极微弱边框
- 光标成为唯一的导航工具
- 将注意力从"页面设计"转移到"用户如何互动"

## 46. 语音优先 (Voice-First Multimodal)
- 极深蓝黑底 #0a0a1a (语音不需视觉噪音)
- 柔和蓝紫文字 #ccd0ee (像语音助手的声音)
- 16px 大圆角亲和界面
- 半透明按钮 + 微光边框
- 声波纹扩散意象，语音为主视觉为辅

## 47. 3D 产品展示 (3D Product Preview)
- box-shadow: 0 8px 30px 深阴影制造悬浮感
- 暖白背景 #fafafa 如摄影棚无影墙
- 黑色单色系统，产品是唯一"内容"
- 12px 精致圆角 + 极简 header
- 家具/时尚/电子电商高端化展示

## 48. 渐变网格 (Gradient Mesh / Aurora Evolved)
- 多层 radial-gradient 光斑 (粉红 + 青色) 在不同位置叠加
- 极透底色卡片 (0.04 不透明) + blur(8px)
- 1px rgba 白 0.06 边框随光斑色彩变化
- 半透明玻璃按钮投射色彩反射
- Aurora UI 的进化版——多色多层网格

## 49. 色差 RGB 分裂 (Chromatic Aberration / RGB Split)
- 三色分离边框：box-shadow 红 1px + 绿 2px + 蓝 3px
- h1 text-shadow: 2px 0 red, -2px 0 blue
- 纯黑底 #000 + DM Mono 等宽终端字体
- hover 时三色边框跳变 (1/2/3 → 2/4/6)
- 摄影光学缺陷转化为刻意的不完美美学

## 50. 复古胶片 (Vintage Analog / Retro Film)
- 暖黄纸色 #f5e8d0 (老照片氧化色调)
- Georgia / Times 衬线字体，16px 1.7 行高
- 深棕 header #3a2a10 (旧书皮色)
- 胶片颗粒卡片 #faf0dd + 棕色柔和阴影
- 古铜色按钮 #8b6914 (旧相机零件色)
- 对印刷和胶片时代的尊重
