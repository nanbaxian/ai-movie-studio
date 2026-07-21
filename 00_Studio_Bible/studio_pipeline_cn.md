# AI Movie Studio Pipeline

Status: CANONICAL_STUDIO_PIPELINE

Planning rule: asset execution must be driven by checked-in documents, not by chat memory. For EP001, use `00_Studio_Bible/asset_library_roadmap_cn.md` as the live execution checklist. When a plan changes, update that file first.

## 核心原则

本项目采用 Studio Pipeline 模式，而不是单集临时制作模式。

目标不是只完成 EP001，而是建立可持续生产数百到上千集短剧的影视资产库。每一集都应该沉淀可复用资产，让后续集数的制作速度和一致性持续提升。

## 推荐总流程

```text
Stage 0  Studio Foundation
Stage 1  Universe Library
Stage 2  Actors Library
Stage 3  Locations Library
Stage 4  Props Library
Stage 5  Family / Relationship Library
Stage 6  Episode Production
```

## EP001 当前执行顺序

```text
Actors
  ↓
Locations
  ↓
Props
  ↓
Relationship Library
  ↓
P002_MASTER Family Portrait
  ↓
Storyboard Image Production
  ↓
Video / Voice / Edit / Publish
```

## 禁止的低效流程

不要按下面方式长期制作：

```text
写剧本
  ↓
临时生图
  ↓
临时视频
  ↓
下一集重新来
```

这种方式适合测试单条短视频，但不适合长期频道和系列化生产。

## 资产优先级

### 1. Actors Library

演员必须先达到可复用标准：

- DNA locked
- Master face
- Multi-angle references
- Expressions
- Actions
- Outfit lock
- Episode production notes
- JSON manifests

### 2. Locations Library

每个场景不是一张图，而是一组可复用视图：

- Front
- Left45
- Right45
- Wide
- Empty
- Day
- Night
- Key prop placement

### 3. Props Library

每个核心道具必须建立状态和角度：

- Front
- Side
- Close
- Holding
- Open
- Closed
- Shot-specific state

### 4. Relationship Library

人物不是孤立存在。每个家庭关系都要可追踪：

- Parent / child
- Sibling
- Grandparent
- Unknown / erased / forgotten member
- Family portrait position
- Memory state

### 5. Master Asset First

EP001 的核心资产是 P002_MASTER 六人全家福。

所有照片变体必须基于 P002_MASTER 编辑，不允许每张重新生成：

- P002-A: complete six-person portrait
- P002-B: Claire removed
- P002-C: Claire and Noah removed
- P002-D: earliest seven-person version with Unknown Man
- P002-E: Emily removed

## 长期收益

第一集会更慢，因为要建立资产库。

从第二集开始，已完成资产可以复用：

- Emily
- Carter family members
- H001 house locations
- Album
- Phone
- Mirror
- Family portrait style
- Visual rules

## EP001 Current Canon Addendum

- Active Claire ID is A006. Older A004 Claire references are legacy and should be corrected when touched.
- H001 core locations are LIVING-DINING, HALLWAY, ROSE-BEDROOM, and ATTIC.
- Mirror coverage belongs to H001-HALLWAY plus P006 Mirror unless the roadmap is explicitly revised.
- Do not generate the 12 final shot images until actors, four core locations, P001-P006, and P002_MASTER/P002 variants are complete.
- The live checklist is `00_Studio_Bible/asset_library_roadmap_cn.md`.

目标是让 EP002 之后的制作成本下降 70% 以上，同时保持角色、场景、道具和世界观一致。
