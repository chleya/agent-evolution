# 项目状态面板

**更新时间**: 2026-03-02

---

## 整体概览

| 项目 | 阶段 | 状态 | 优先级 |
|------|------|------|--------|
| NeuralSite | Stage 4 W1-W2 | 进行中 | P0 |
| Evo-Swarm | 运行中 | 稳定 | P1 |
| Visual CoT | 刚启动 | 建设中 | P1 |
| 优化企划书 | v2.1发布 | 已就绪 | - |

---

## NeuralSite 施工管理系统

**位置**: `F:\drawing_3d`  
**GitHub**: https://github.com/chleya/drawing-3d

### 阶段进度

| Stage | 内容 | 状态 |
|-------|------|------|
| Stage 1 | 全视之眼（感知） | ✅ 完成 |
| Stage 2 | 语义化蓝图 | ✅ 完成 |
| Stage 3 | 自动驾驶 | ✅ 完成 |
| Stage 4 | 商业部署 | 🔄 W1-W2进行中 |

### 核心组件

- ✅ 语义API (端口5001) - 运行中
- ✅ 知识图谱 (13节点)
- ✅ LLM集成 (MiniMax)
- ✅ 浏览器自动化 (Playwright)
- ⏳ Neo4j部署
- ⏳ 实际图纸数据加载

### 已加载文档

- ✅ 六维时空AI施工管理系统企划书
- ✅ 三维空间坐标语义化技术解决方案
- ✅ 技术详细规格说明书

### 待处理

- [ ] 实际图纸数据（CAD/PDF）
- [ ] 规范数据（JTG F40-2004等）

### 最新Commit

```
847c65f docs: add 技术详细规格说明书
107816d docs: add 三维空间坐标语义化方案
aee9d46 docs: add 六维时空企划书
```

---

## Evo-Swarm 演化智能体

**位置**: `F:\skill\evo_swarm`  
**GitHub**: https://github.com/chleya/Evo-Swarm

### 核心能力

- ✅ 思维链系统（思考→计划→执行→验证→反思）
- ✅ 记忆树（Memory Tree）
- ✅ 多智能体协作（94%成功率）

### 最新模块

- `visual_chain_of_thought.py` - 视觉思维链

### 最新Commit

```
9b7e435 docs: add Visual CoT project introduction
a100a0a feat: add Visual Chain of Thought
```

---

## 视觉思维链 (Visual CoT)

**位置**: `F:\skill\evo_swarm\visual_chain_of_thought.py`

### 架构

```
看(截图) → 理解(Qwen-VL) → 推理(LLM) → 行动
     ↑                                      ↓
     └────────── 思维链历史 ←───────────────┘
```

### 集成资源

- PhoneDriver: `F:\PhoneDriver\` (Qwen-VL + ADB)
- Playwright: 网页自动化

### 待完成

- [ ] Qwen-VL集成
- [ ] 完整闭环测试
- [ ] 施工巡查Demo
- [ ] 图纸理解模块

---

## 优化企划书

**版本**: v2.1 (2026-03-02)

### 阶段规划

| 阶段 | 时间 | 任务 |
|------|------|------|
| 第一阶段 | Week 1-2 | 记忆系统、项目面板 |
| 第二阶段 | Week 3-4 | 知识关联、主动建议 |
| 第三阶段 | Month 2-3 | 深度整合、实用化 |

### 当前任务 (Week 1-2)

- [x] 统一记忆格式
- [ ] 项目状态面板 ← 当前
- [ ] 每周简报模板
- [ ] 主动思考清单

---

## 核心理念

> **"70%真实 > 100%幻觉"**
> — Chen Leiyang, 2026-02-07

> **"完美的共识是不可达到的，但鲁棒的共识是可实现的"**

---

## 技术栈

| 层级 | 技术 |
|------|------|
| 后端 | Python + Flask + PostgreSQL + Neo4j |
| 前端 | Cesium + Three.js |
| AI | MiniMax LLM + Qwen-VL |
| 自动化 | Playwright + ADB |

---

*每周更新*
