# Quant
Some backtesting results of my own built BASIC strategies.

多因子沪深300指数增强：
1. 沪深300为标的
2. 已设置避免未来数据
3. 已设置交易滑点和手续费
4. 已设置持仓数量和调仓频率
5. 已加入大盘止损
6. 已过滤停牌股票
7. 策略为取基本面因子，逐项进行排名，乘以权重后取平均排名最高的前n只股标买入，定期调仓 
