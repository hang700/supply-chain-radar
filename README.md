# 供应链风险雷达 (Supply Chain Risk Radar)

基于多Agent协同的全供应链风险预警与推理系统。

## 架构
- **CrawlerAgent** - 全球情报实时爬取
- **EntityAgent** - 实体抽取与物料关联
- **CausalAgent** - 动态知识图谱与长链推理（>12步）
- **PlanAgent** - 多预案自动生成
- **SimAgent** - 离散事件沙盘推演

## 核心能力
将传统人工2天的分析流程压缩至15分钟，并能发现三阶以上传导风险。

## 运行演示
```bash
python supply_chain_radar_demo.py
