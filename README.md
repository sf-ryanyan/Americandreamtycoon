# 🎲 American Dream Tycoon · 美国梦大亨

**Buy US states, build hotels, collect rent, and become the richest tycoon in America.**
**买下美国各州，盖房盖酒店，收租致富，成为全美最强地产大亨！**

A cartoon board game that runs in your web browser. Play with 2–3 friends on one screen, or against computer players.
一款可以直接在浏览器里玩的卡通桌游。2–3 人同屏轮流玩，也可以和电脑对战。

![Gameplay 游戏画面](screenshots/gameplay.png)

---

## ✨ Features · 游戏特色

| | English | 中文 |
|---|---|---|
| 🗺️ | 40-tile board with 24 US states in 8 color groups, plus a live US map in the middle | 40 格棋盘，24 个州分成 8 个颜色组，中间是实时更新的美国地图 |
| 🎲 | One 7-sided die. **7 is lucky**: roll a 7 and go again | 一颗 7 面骰子，**7 是幸运数字**，掷出 7 再走一次 |
| 🏠 | Upgrade: Empty lot → 1 House → 2 Houses → Hotel → Luxury Hotel | 升级：空地 → 一栋房子 → 两栋房子 → 酒店 → 豪华酒店 |
| 🤠 | 6 themed characters (no special powers, so the game stays fair) | 6 个主题角色（没有技能，保证公平） |
| 🤖 | AI players: Normal or Hard | 电脑玩家：普通 / 困难 |
| 🔥 | Comeback rules: wild cards for players far behind, a Comeback Wheel, and tougher cards for the leader | 翻盘机制：落后者极端卡、逆天改命转盘、领先者"树大招风" |
| 🎰 | Vegas casino, jail, hospital, IRS, railroads, airports and utilities | 拉斯维加斯赌场、监狱、医院、国税局、铁路、机场、公共事业 |
| 🌐 | Chinese / English with one click | 中英文一键切换 |
| 📦 | One HTML file. No install, no server, no login | 只有一个 HTML 文件，不用安装、不用服务器、不用登录 |

## 🧑‍🤝‍🧑 Characters · 角色

| Character 角色 | Who 身份 |
|---|---|
| Tex | Texas Cowboy 德州牛仔 |
| Sam | Silicon Valley Geek 硅谷极客 |
| Stella | Hollywood Star 好莱坞明星 |
| Mr. Gold | Wall Street Mogul 华尔街大亨 |
| Kai | Hawaiian Surfer 夏威夷冲浪手 |
| Rosa | Star Realtor 金牌地产经纪 |

## ⚙️ Game Setup · 开局设置

![Setup 开局设置](screenshots/setup.png)

| Option 选项 | Choices 可选 |
|---|---|
| Players 玩家人数 | 2 or 3 |
| Each seat 每个座位 | Human 真人 / AI Normal 电脑·普通 / AI Hard 电脑·困难 |
| Starting cash 起始资金 | $800K · $1.5M · $3M · $5M |
| Game ends 结束方式 | Round limit 固定回合 · First bankruptcy 第一人破产 · Last one standing 玩到最后一人 |
| Rounds 回合数 | 15 · 25 · 40 · 60 |

## 📖 How to Play · 玩法说明

**Each turn · 每回合**
1. Roll the die and move. 掷骰子前进。
2. Pass GO to collect **$200K**. 经过起点领工资 **$200K**。
3. Unowned property: buy it or pass. 无人的地：可以买，也可以不买。
4. Someone else's property: pay rent. 别人的地：付租金。
5. Your own state: pay to upgrade 1 or 2 levels. 自己的州：可以付费升 1 级或 2 级。

**Key rules · 重要规则**
- **Color set:** own all 3 states of a color and every rent level is ×2. 集齐同色 3 个州，所有租金 ×2。
- **Rent inflation:** every 5 rounds, all rents go up 50%. 每 5 轮全场租金 +50%。
- **Jail:** pay $100K, use a jail card, or roll 6 or 7 to get out. 监狱：付 $100K、用出狱卡，或掷出 6 或 7 出狱。
- **Casino:** bet Small (1–3) or Big (5–7). A 4 means the house wins. 赌场：押小（1–3）或押大（5–7），掷出 4 庄家赢。
- **Comeback Wheel:** below 30% of the leader's net worth, you may spin it (take 30% of the leader's cash, +$800K, nothing, or lose half your cash). 资产低于第一名 30% 时可转盘：拿走第一名 30% 现金 / +$800K / 什么都没有 / 失去一半现金。
- **Out of cash:** buildings are sold back at half price, then land is mortgaged. If that is still not enough, you are bankrupt. 没钱时自动半价拆建筑、再抵押地产，还不够就破产。
- **Net worth** = cash + land price + building investment. 总资产 = 现金 + 地价 + 建筑投入。

Full rules are inside the game (**规则 / Rules** button). 完整规则在游戏里的「规则」按钮。

**Tips · 小提示**
- Best on a computer or tablet in landscape. 推荐电脑或平板横屏玩。
- Tap any tile or state on the map to see its deed. 点击格子或地图上的州可以查看地契。
- Press **Space** for the main button. 按**空格键** = 主按钮。

## 🚀 Run It Yourself · 自己部署

**Option 1: Just open it · 直接打开**
Download `index.html` and double-click it. It opens in your browser.
下载 `index.html`，双击就能在浏览器里玩。

**Option 2: GitHub Pages (free hosting) · 免费上线**
1. Upload `index.html`, `README.md` and the `screenshots` folder to a GitHub repo.
   把 `index.html`、`README.md` 和 `screenshots` 文件夹上传到 GitHub 仓库。
2. Go to **Settings → Pages**.
   打开 **Settings → Pages**。
3. Under **Branch**, pick `main` and `/ (root)`, then click **Save**.
   在 **Branch** 选 `main` 和 `/ (root)`，点 **Save**。
4. Wait 1–2 minutes. Your game is live at `https://<your-username>.github.io/<repo-name>/`.
   等 1–2 分钟，游戏就上线了。

## 🛠️ Tech · 技术说明

- Plain HTML, CSS and JavaScript in one file. No frameworks, no build step.
  纯 HTML + CSS + JavaScript，单个文件，不需要框架或打包。
- All characters, landmarks and buildings are hand-drawn SVG, so they look the same on every device.
  角色、地标和建筑全部是 SVG 矢量图，任何设备显示都一样清晰。
- Sound effects are made in the browser with the Web Audio API (no audio files).
  音效由浏览器实时生成，没有音频文件。
- Settings (language, sound, last setup) are saved in your browser's local storage.
  语言、声音和上次的设置会保存在你的浏览器里。

## 🙏 Credits · 致谢

- US state shapes: [us-atlas](https://github.com/topojson/us-atlas) (ISC License), based on U.S. Census Bureau cartographic boundary files.
  美国州界数据来自 us-atlas，源自美国人口普查局。
- Fonts: [Lilita One](https://fonts.google.com/specimen/Lilita+One) and [Fredoka](https://fonts.google.com/specimen/Fredoka) from Google Fonts (SIL Open Font License).
  字体来自 Google Fonts。
- Inspired by classic property-trading board games. This is an original game and is not affiliated with any board game brand.
  灵感来自经典地产桌游。本游戏为原创作品，与任何桌游品牌无关。

---

Created by **Ryan Yan** · sfryanyan@gmail.com
© 2026 Ryan Yan. All rights reserved.
