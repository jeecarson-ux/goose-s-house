# 客服运营 Agent Skills

面向客服运营、eCall、需求管理和工作交接的三个独立标准 Agent Skills。

## Skills
- [business-analysis](skills/business-analysis/SKILL.md)：业务数据分析、异常定位、运营复盘和改善验证。
- [requirements-writing](skills/requirements-writing/SKILL.md)：需求背景、功能规则、收益测算、验收标准与评审材料。
- [work-sop](skills/work-sop/SKILL.md)：工作手册、SOP、系统维护、异常升级与交接。

## 目录结构
```
skills/
  business-analysis/
    SKILL.md
    references/analysis-template.md
  requirements-writing/
    SKILL.md
    references/requirements-template.md
  work-sop/
    SKILL.md
    references/sop-template.md
CONTRIBUTING.md
```

## 使用
将所需 Skill 文件夹放入兼容 Agent Skills 的工具支持的 skills 目录。每个 Skill 使用 YAML frontmatter 的 `name` 和 `description` 作为发现元数据。

## 设计原则
1. 先核对事实和口径，再形成结论。
2. 区分事实、推断、假设与待确认项。
3. 不虚构数据、规则、系统能力、负责人或收益。
4. 输出必须可评审、可执行、可验收或可交接。
5. 修改已有材料时保留有效内容与关键案例，不擅自删减。
6. 客户、车辆及内部运营数据按需脱敏。

