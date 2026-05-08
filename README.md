# 关键用法

Analyze the Xuanwu Gate Incident.

Use:
- historical-expansion
- narrative-hooks
- character-network
- butterfly-effect
- ordinary-reader
- story-structure

Generate:
- article.md
- timeline.json
- relationships.json
- youtube_script.md

# 核心工作流

------

# STEP 1

# 选择一个历史入口

例如：

- 官渡之战
- 安史之乱
- 指鹿为马
- 玄武门之变
- 岳飞
- 霍去病

------

# STEP 2

# Codex 自动扩展历史关系

你输入：

```
codex
```

然后：

```
分析“玄武门之变”：
生成：
1. 核心人物
2. 人物关系树
3. 时间线
4. 相关成语
5. 前因后果
6. 后世影响
7. 同时代事件
8. 可故事化节点
```

Codex 会：

- 自动创建 markdown
- 自动建立 JSON
- 自动生成关系文件

例如：

```
people/li_shimin.md
people/li_jiancheng.md
events/xuanwu_gate_incident.md
relations/tang_royal_family.json
```

------

# STEP 3

# 自动生成故事节点

这是核心。

你需要训练 Codex：

不要写百科。

而是：

# 生成“戏剧节点”

例如：

```
dramatic_nodes:
  - 李世民被逼入绝境
  - 长孙无忌秘密布局
  - 尉迟敬德冲宫
  - 李渊震惊
  - 太子集团崩溃
```

这一步决定：

> 能不能让普通人读下去。

------

# STEP 4

# 自动生成“历史扩展”

这是你最重要的特色。

例如：

```
扩展：
- 为什么叫玄武门？
- 唐朝宫门制度
- 李渊为什么优柔寡断？
- 玄武门之变对后世皇权的影响
- 与靖难之役的相似性
```

这一步会形成：

# 「历史宇宙感」

读者会感觉：

整个历史在互相连接。

------

# STEP 5

# 自动生成多种内容格式

这是 Codex 最大优势之一。

你可以让它：

------

## 生成：

### 1. 长文章

```
outputs/article.md
```

------

### 2. B站视频稿

```
outputs/bilibili_script.md
```

------

### 3. Shorts/短视频脚本

```
outputs/short_video_hooks.md
```

------

### 4. 时间线 JSON

```
timeline.json
```

------

### 5. 人物关系图

```

```

------

### 6. 播客文稿

------

### 7. 小红书版本

------

### 8. 知乎版本

------

# 四、你必须建立的 Skills

这部分才是核心。

------

# 1. Historical Expansion Skill

（历史扩展 skill）

作用：

从一个点扩展：

- 人
- 事
- 制度
- 地点
- 家族
- 后世影响

------

# 2. Narrative Hook Skill

（故事钩子 skill）

作用：

自动生成：

- 开场悬念
- 冲突
- 反转
- 结尾回扣

例如：

```
“唐朝最危险的一天，
不是安史之乱，
而是李世民杀兄弟那天。”
```

------

# 3. Character Network Skill

（人物关系网 skill）

自动生成：

```
relations:
  ally:
  enemy:
  family:
  mentor:
  political:
```

这是最吸引普通人的部分。

------

# 4. Idiom Connection Skill

（成语关联）

例如：

写：

鸿门宴

自动扩展：

- 项庄舞剑
- 人为刀俎我为鱼肉
- 沛公
- 范增
- 刘邦后续

普通人会非常喜欢。

------

# 5. Butterfly Effect Skill

（历史蝴蝶效应）

例如：

```
如果没有安禄山，
唐朝可能不会衰落。
```

或者：

```
一个宦官如何改变了整个王朝。
```

这会极大增强阅读欲。

------

# 6. Human Drama Skill

（人性戏剧）

重点：

不是历史事件。

而是：

# “人在极端局势中的选择”

例如：

- 猜忌
- 背叛
- 忠诚
- 权力
- 恐惧

------

# 7. Timeline Compression Skill

（时间压缩）

把：

10年历史

压成：

10分钟故事。

这是历史内容创作者最关键能力之一。

------

# 8. Historical Atmosphere Skill

（时代氛围）

生成：

- 市井
- 战场
- 宫廷
- 气味
- 礼仪
- 服饰

让历史“活起来”。

------

# 五、你应该怎么组织 skills 文件

你应该建立：

```
skills/
```

下面：

------

## skills/historical_expansion.md

定义：

```
当分析一个历史事件时：

必须扩展：
1. 人物关系
2. 家族关系
3. 前因
4. 后果
5. 制度背景
6. 成语关联
7. 同时代事件
8. 后世影响
```

------

## skills/narrative_hooks.md

定义：

```
文章开头必须：
- 制造危险感
- 制造反差
- 制造悬念
```

------

## skills/ordinary_reader.md

定义：

```
禁止：
- 学术腔
- 论文感
- 长段落
- 纯编年史
```

------

## skills/story_flow.md

定义：

```
每隔500字：
必须：
- 一个转折
- 一个认知奖励
- 一个新的秘密
```

------

# 六、最关键：

# AGENTS.md

这是 Codex 灵魂。

例如：

```
# Historical Storytelling Engine

目标：
为普通人生成高可读性的历史故事。

核心原则：

- 故事优先
- 人物优先
- 戏剧优先
- 历史真实
- 避免论文感

必须：
- 自动扩展关系
- 自动扩展成语
- 自动扩展后续影响
- 自动生成故事节点

禁止：
- 流水账
- 空洞总结
- Wikipedia 风格
```

Codex 会长期记住。

------

# 七、最适合你的输出格式

你未来应该：

# Markdown + JSON 双系统

------

# Markdown

用于：

- 文章
- 视频稿
- 故事

------

# JSON

用于：

- 人物关系
- 时间线
- 事件图谱

例如：

```
{
  "person": "李世民",
  "father": "李渊",
  "siblings": ["李建成","李元吉"],
  "major_events": [
    "玄武门之变"
  ]
}
```

这样未来可以：

- AI 检索
- 自动生成
- 图数据库
- 网站
- App

------

# 八、未来高级玩法（非常适合你）

以后你甚至可以：

------

# 1. 自动生成“历史宇宙”

类似：

- 漫威宇宙
- 冰火世界

但是真实历史。

------

# 2. 自动人物关系图

------

# 3. 自动视频脚本工厂

------

# 4. 自动系列化

例如：

```
“大唐权力游戏”
```

自动生成几十集。

------

# 九、你真正的竞争力

不是：

“比别人懂历史”。

而是：

# 「把历史变成连续沉浸体验」

这是完全不同的东西。

------

# 十、最适合你的技术栈（推荐）

推荐：

- Markdown
- JSON
- Mermaid
- Obsidian
- Codex CLI
- Git
- VSCode

------

# 十一、最推荐的实际模式

推荐：

## Obsidian + Codex

因为：

你本质是在做：

# 「历史知识网络」。

这和 Obsidian 极其匹配。