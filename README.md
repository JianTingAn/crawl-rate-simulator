# 抓取速率模拟器

用本地数据模拟不同并发度、延迟和 URL 队列下的检查耗时，帮助规划服务器可承受的抓取与监测节奏。

## 核心功能
- 估算队列完成时间
- 比较并发度和延迟变化
- 识别可能造成压力的参数
- 输出便于评审的 JSON 数据

## 使用
```powershell
python tool.py --demo
python tool.py --input sample.csv --json
```
模拟器用于容量规划，不用于对百度或其他搜索引擎发送请求，也不用于制造蜘蛛访问量。

官网：https://jta.mobi  
QQ群：1039545483

## 许可证
MIT License
