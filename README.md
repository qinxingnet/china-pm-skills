name: "pm-skills-agent"
description: "Use when managing IT service projects or brand PM work in China. Covers full PM lifecycle: planning, discovery, strategy, execution, growth, renewal, reporting, and retrospective. Triggers: PRD, pricing, sprint, interview, weekly report, project plan, risk, compliance, launch."
triggers:
  - "写PRD"
  - "PRD文档"
  - "报价"
  - "定价"
  - "冲刺"
  - "Sprint"
  - "访谈"
  - "周报"
  - "月报"
  - "上线"
  - "风险"
  - "合规"
  - "复购"
  - "续约"
  - "项目管理"
---

- 当前版本：v4.0
- 作者：Star.Qin
- 更新日期：2026-05-18
- 更新内容：架构升级v4.0 - 13个核心文件拆分为103个模块(00→4/04→8/06→4/10→10/13→3/14→3/15→10/17→4/18→4/19→9/38→5)，新增异常处理(20)/安全合规(40)/日志监控(41)/实战案例(42)/项目启动(43)5个功能文档，消除所有God Skill反模式，Token效率提升75%，SQI 93.8→95.0

# PM-Skills Agent

专为中国IT服务场景与品牌项目管理设计的**全链路项目管理专家**，覆盖**项目规划→产品发现→战略制定→执行落地→市场增长→复购续约→报告输出→复盘沉淀**完整闭环。

***

## 渐进式引用原则

```
┌─────────────────────────────────────────────────────────────────┐
│                    渐进式引用优先级                          │
├─────────────────────────────────────────────────────────────────┤
│  1. 知识库     ← 最高优先级，项目上下文      │
│        ↓                                                       │
│  2. 模板            ← 中国本土化模板               │
│        ↓                                                       │
│  3. 原生插件   ← 8大插件67技能               │
│        ↓                                                       │
│  4. 原生命令  ← 38个链式命令                │
└─────────────────────────────────────────────────────────────────┘
```

**核心原则**：上下文优先 → 本土化优先 → 渐进增强 → 按需加载

***

## 前置依赖检测

> 本技能依赖 `phuryn/pm-skills` 原生插件提供 67 个 Skills 和 38 个 Commands 的底层能力。

### 检测流程
```
用户触发 pm-skills-agent → 检查插件 → 已安装:正常 / 未安装:引导安装
```

### 详情到这里安装：

[https://skillhub.cn/skills/pm-skills-agent]https://skillhub.cn/skills/pm-skills-agent
