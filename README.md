# 五子棋人机对战

一个简单的网页版五子棋游戏，支持玩家与 AI 对战。

## 功能特性

- 🎮 玩家 vs AI 人机对战
- 🧠 AI 智能算法（评分系统）
- ↩️ 支持悔棋
- 🔄 重新开始
- 🎯 自动胜负判定（五子连珠）

## 如何开始

### 本地运行

```bash
# 克隆项目
git clone https://github.com/williamxiewz-bot/gomoku.git
cd gomoku

# 启动本地服务器
python3 -m http.server 8080
```

然后打开浏览器访问：http://localhost:8080

## 玩法说明

1. 你执黑子（先手）
2. AI 执白子（后手）
3. 点击棋盘落子
4. AI 会自动思考并反击
5. 五子连珠即获胜

## 技术栈

- HTML5
- CSS3
- JavaScript (原生)

## 许可证

MIT
