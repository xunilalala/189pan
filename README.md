## [![云盘签到](https://github.com/y377/189pan/actions/workflows/main.yml/badge.svg)](https://github.com/y377/189pan/actions/workflows/main.yml) 189pan 

> 天翼云盘（支持多账号）自动签到

###### 本项目fork自[Cloud189_Action](https://github.com/qsf728999746/Cloud189_Action)（在此感谢）并修复和改进以下内容：
1. 每天两次签到，当第一次签到时，未正常显示“抽奖获得的容量数”，原代码仅显示“抽奖获得1” 修复状态：✅
2. 每天两次签到，当第二次签到时，未正常显示“抽奖获得的容量数”，原代码仅显示`{"errorCode":"User_Not_Chance","errorMsg":"sessionKey=马赛克,activityId=ACT_SIGNIN,ExcuteOverLimitedNumError!"}`；暴露的`sessionKey`我不知道具体作用，但是避免风险显示，顾修复 修复状态：✅
3. 将每日签到和抽奖数据直接通过GitHub pages展示 改进状态：✔️
