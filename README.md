# Image Confirmed
**包括绘制脚本，数据和图表**
## background

### 0.duration_CDF
- **duration_CDF.pdf**: 请求时间 CDF

### 1.cold_starts
- **Cold_Starts_busiest_30min_by_minute.png**: Cold start 原始值半小时的柱状图
- **Cold_Starts_busiest_30min_comparison_smoothed.png**: Cold start 半小时原始值和平滑值的折线图

### 2.带状图&比例折线图
- **prewarm_stacked_bands_only_d05.png**: Active instance 带状图
- **prewarm_ratio_only_d05.png**: 比例折线图
- **replot_stacked_bands_formatted.png**: 重新绘制的带状图（格式化版本）
- **replot_ratio_curve_formatted.png**: 重新绘制的比例曲线（格式化版本）

### 3,4.mem&hit
- **memory_cdf_d05.png**: 内存 CDF 图
- **hit_rate.csv** 在不同lookahead和mem_limit配置下的hit rate

## evaluation

### 5,6.slowdown&latency
- **comparison_kf_k8s_dirigent.pdf**: KF vs K8s vs Dirigent 对比图
- **slowdown_p95_bar.pdf**: Slowdown P95 柱状图
- **slowdown_p99_bar.pdf**: Slowdown P99 柱状图

### 7.mem vs latency pareto
- **pareto_prewarm.png**: Prewarm 的 Memory vs Latency Pareto 图

### original（旧图）
- **Latency Comparison - KF vs K8s with Different API Factors.pdf**: KF vs K8s 在不同 API Factors 下的 latency CDF
- **Slowdown Comparison - KF vs K8s with Different API Factors.pdf**: KF vs K8s 在不同 API Factors 下的 Slowdown CDF
- **Resource vs Latency - kd vs Prewarm.png**: kd vs k8s Prewarm 的 Resource vs Latency 图
