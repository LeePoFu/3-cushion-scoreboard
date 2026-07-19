# Scoreboard v1.4 Integration

## 功能按鈕順序
白球出杆：
- 暫停
- 換黃球 →
- 上一步
- 結束比賽

黃球出杆：
- 暫停
- 上一步
- ← 換白球
- 結束比賽

## Records 同步
- 可指定白球或黃球為「我」。
- 比賽結束時保存 Scoreboard 原始紀錄。
- 同步寫入 threeCushionTrainingLog_v1。
- externalMatchId 避免重複同步。
- 讓分與實際得分分開保存。
