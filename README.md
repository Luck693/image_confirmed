# Image Confirmed

## background

- **Cold_Starts_busiest_30min_by_minute.png**: Cold start 原始值半小时的柱状图
- **Cold_Starts_busiest_30min_comparison_smoothed.png**: Cold start 半小时原始值和平滑值的折线图
- **duration_CDF.pdf**: 请求时间 CDF
- **prewarm_stacked_bands_10_0.png**: Cold function keepalive 0min，hot function keepalive 10min 的 active instance 带状图
- **prewarm_stacked_bands_10_10.png**: 都 keepalive 10min 的带状图

## evaluation

- **Latency Comparison - KF vs K8s with Different API Factors.pdf**: KF vs K8s 在不同 API Factors 下的 latency CDF
- **Slowdown Comparison - KF vs K8s with Different API Factors.pdf**: KF vs K8s 在不同 API Factors 下的 Slowdown CDF
- **Resource vs Latency - kd vs Prewarm.png**: kd vs k8s Prewarm 的 Resource vs Latency 图
