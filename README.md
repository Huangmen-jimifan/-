# 明日方舟投票榜数据分析

> 数据来源：[ArknightsVote 仓库](https://github.com/ArknightsVote/ArknightsVote)  
> 投票统计周期：2024年2月19日 05:00 至 2月26日 04:59  
> 分析版本：V1.0


## 文件结构说明

| 文件名 | 类型 | 说明 |
|--------|------|------|
| `明日方舟投票榜数据分析-V1.0.pdf` | PDF | 📊 主体分析报告，完整介绍数据处理、模型构建与结论 |
| `role.csv` | CSV | 干员基本信息，包括编号、名称、实装时间等 |
| `win_lose_matrix.csv` | CSV | 从原始投票数据统计而成的胜负矩阵（106 × 106） |
| `soft_cluster_result.csv` | CSV | 层次聚类结果（簇数 $k=10$）下每位干员的簇归属情况 |
| `soft_cluster_result_2.csv` | CSV | 两簇软聚类分析结果（含隶属度指标） |
| `probability_vs_date.pdf` | PDF | 干员强度指标随实装时间分布变化图（软隶属度 vs. 时间） |