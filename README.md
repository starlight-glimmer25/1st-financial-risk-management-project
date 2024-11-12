English Version
Automated Financial Risk Monitoring System
Project Overview
This project is an automated risk monitoring system designed to quantify and monitor market risk through Value at Risk (VaR) and Expected Shortfall (ES) metrics. The project utilizes both historical financial data and simulated data to simulate real-time risk assessment. This system provides a comprehensive framework for understanding and managing portfolio risk.

Project Files
risk-management.py: This script covers the initial four days of tasks, including data cleaning, calculation of log returns, and preliminary VaR and ES computation. It also addresses data issues such as missing values and zero entries to ensure accurate metrics.
systemriskvar.py: This script covers the final three days of tasks. It uses simulated data to substitute real-time API data and carries out the automated risk control process. The system monitors risk continuously and provides backtesting of VaR and ES values using various metrics such as breach rate and Mean Squared Error (MSE).
Features
Data Cleaning: Cleans and prepares financial data for analysis, addressing zero and missing values, and calculating log returns.
Rolling VaR and ES Calculation: Computes rolling VaR and ES values, updated periodically to capture ongoing changes in asset risk.
Simulated Data for Real-Time Testing: Uses randomly generated data in place of API data for real-time simulation of risk monitoring.
Backtesting Framework: Analyzes the accuracy of VaR and ES predictions based on historical breach rates and MSE for model performance evaluation.
Comprehensive Visualization: Visualizes log returns and calculated risk levels, enabling clear insights into risk over time.
Instructions
Prepare Data: Ensure historical data is available in financial_data_log.csv and path locations are set correctly within each script.
Execute Scripts:
Run risk-management.py for initial data cleaning, calculation of log returns, and preliminary risk evaluation.
Run systemriskvar.py for automated risk monitoring and backtesting using simulated real-time data.
Analyze Output: View the system_VaR.csv and system_ES.csv files for saved VaR and ES metrics. These files provide insight into the calculated risk values over the project’s rolling time frames.
Future Enhancements
API Integration: Replace simulated data with real-time API data to improve real-world application.
Model Tuning: Enhance the VaR and ES accuracy by optimizing parameters such as window size and confidence level.
Advanced Machine Learning: Introduce machine learning models for predictive risk monitoring and forecasting.
中文版本
自动化金融风险监控系统
项目概述
本项目是一个自动化风险监控系统，旨在通过 VaR（风险价值）和 ES（预期损失）量化并监控市场风险。项目结合了历史金融数据和模拟数据，实现了准实时的风险评估，为理解和管理投资组合风险提供了全面的框架。

项目文件
risk-management.py：此脚本涵盖前四天的任务，包括数据清洗、对数收益率计算以及初步的 VaR 和 ES 计算。此文件解决了数据缺失及零值等问题，以确保计算准确。
systemriskvar.py：此脚本涵盖最后三天的任务，使用随机生成的数据替代实时 API 数据进行风险监控。系统通过连续监控风险，并基于历史突破率和均方误差（MSE）对 VaR 和 ES 值进行回测。
主要功能
数据清洗：对金融数据进行清洗和准备，处理零值和缺失值，并计算对数收益率。
滚动计算 VaR 和 ES：基于滚动窗口计算 VaR 和 ES 数值，以捕捉资产风险的持续变化。
模拟数据实时测试：使用随机生成的数据替代 API 数据，模拟实时风险监控。
回测框架：通过历史突破率和 MSE 评估 VaR 和 ES 预测的准确性，并进行模型性能评价。
可视化分析：展示对数收益率及风险水平的变化，提供直观的风险分析。
使用说明
准备数据：确保 financial_data_log.csv 文件中包含历史数据，并正确设置文件路径。
执行脚本：
运行 risk-management.py 完成初始的数据清洗、对数收益率计算以及基础风险评估。
运行 systemriskvar.py 完成自动化风险监控和基于模拟数据的回测。
分析输出：查看 system_VaR.csv 和 system_ES.csv 文件中保存的 VaR 和 ES 指标。这些文件展示了项目滚动时间框架内计算的风险值。
未来改进方向
API 集成：用实时 API 数据替换模拟数据，以增强系统的实际应用。
模型调优：通过优化窗口大小和置信水平，提高 VaR 和 ES 的预测准确性。
高级机器学习：引入机器学习模型，实现更精准的风险预测和监控。
