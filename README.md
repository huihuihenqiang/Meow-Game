## 🐱 猫了个猫 - 小程序游戏介绍 🐱

### 游戏简介 😸

《猫了个猫》是一款简单有趣的消除类小程序游戏。玩家需要通过点击三个相同的图案来进行消除，达到通关目标。游戏界面设计精美，将各种功能巧妙地融合在了贴画中，例如排行榜是黑板，音乐开关是音响，充满了创意和趣味。

### 游戏特色 🐾

- **开始页面**：在这个页面，你可以看到各种功能按钮。排行榜被设计成黑板的样子，音乐开关被设计成音响，整体风格温馨可爱。🍰

![cfd9661a0e7bc65e74b3f83f7190aa8](https://github.com/huihuihenqiang/Meow-Game/assets/99072450/4d60bcf3-dcdf-4d50-82fe-1c4a832142b7)

- **游戏页面**：在主游戏页面，你需要点击三个一样的图案来进行消除。游戏简单但具有挑战性，非常适合消磨时间。🎮

![01d2c8ca64bb400f478f8f8943e2007](https://github.com/huihuihenqiang/Meow-Game/assets/99072450/e7998ac1-ff4d-46cc-bad0-94d672a0e38d)


### 如何开始 🎯

1. 点击“开始游戏”按钮进入主游戏页面。🚀
2. 在主游戏页面，通过点击三个相同的图案来进行消除。💡
3. 达到关卡目标即可通关。🏆

### 下载和安装 🛠️

1. 下载微信开发者工具和Cocos Creator
    - **微信开发者工具**：[微信开放文档](https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html)
    - **Cocos Creator**：[Cocos引擎_游戏开发引擎](https://www.cocos.com/creator)
    
2. 发布流程：
    - 在Cocos中编写游戏，然后生成对应的软件包，再到微信开发者工具上传到微信小程序平台。

### 开发游戏 🚀

Cocos是典型的组件节点式的开发，3.x版本之前的语言是JS和TS都可以使用。3.x版本之后只能使用TS。详细使用说明请参考：[Introduction · Cocos Creator使用手册](https://docs.cocos.com/creator/manual/zh/)

### 微信小游戏发布的几个功能 📲

1. 添加分享功能：

    ```javascript
    var id = '' // 通过 MP 系统审核的图片编号
    var url = '' // 通过 MP 系统审核的图片地址
    wx.shareAppMessage({
      imageUrlId: id,
      imageUrl: url
    })
     
    wx.onShareAppMessage(function () {
      return {
        imageUrlId: id,
        imageUrl: url
      }
    })
    ```

2. 添加广告功能：

    ```javascript
    let bannerAd = wx.createBannerAd({
      adUnitId: 'xxxx',
      style: {
        left: 10,
        top: 76,
        width: 320
      }
    })
     
    bannerAd.show()
    ```

### 游戏链接 🎮

点击下面的链接即可开始游戏：

![d4b9a8ad0c9e4e3c8be5031572df27fc](https://github.com/huihuihenqiang/Meow-Game/assets/99072450/c628f94a-2c7a-4781-8f8a-5a59efcbecd8)




---

## 🐱 Meow Game - Mini Program Introduction 🐱

### Game Introduction 😸

"Meow Game" is a simple and fun elimination mini-program game. Players need to eliminate three identical patterns by clicking on them to reach the goal. The game interface is beautifully designed, cleverly integrating various functions into the stickers, such as the leaderboard as a blackboard and the music switch as a speaker, full of creativity and fun.

### Game Features 🐾

- **Start Page**: On this page, you can see various function buttons. The leaderboard is designed as a blackboard, and the music switch is designed as a speaker. The overall style is warm and cute. 🍰

![cfd9661a0e7bc65e74b3f83f7190aa8](https://github.com/huihuihenqiang/Meow-Game/assets/99072450/0d402af0-21a9-43fd-acb2-2d0816eaa76e)

- **Game Page**: On the main game page, you need to eliminate three identical patterns by clicking on them. The game is simple but challenging, perfect for passing the time. 🎮

![01d2c8ca64bb400f478f8f8943e2007](https://github.com/huihuihenqiang/Meow-Game/assets/99072450/9548e638-ee3f-47b3-af45-e85d0dfec1ea)


### How to Start 🎯

1. Click the "Start Game" button to enter the main game page. 🚀
2. On the main game page, eliminate three identical patterns by clicking on them. 💡
3. Reach the level goal to pass the level. 🏆

### Download and Install 🛠️

1. Download WeChat Developer Tools and Cocos Creator
    - **WeChat Developer Tools**: [WeChat Open Docs](https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html)
    - **Cocos Creator**: [Cocos Engine_Game Development Engine](https://www.cocos.com/creator)
    
2. Publishing Process:
    - Develop the game in Cocos, generate the corresponding package, and then upload it to the WeChat Mini Program platform using WeChat Developer Tools.

### Game Development 🚀

Cocos is a typical component-node development system. Before version 3.x, both JS and TS languages can be used. After version 3.x, only TS can be used. For detailed usage instructions, please refer to: [Introduction · Cocos Creator User Manual](https://docs.cocos.com/creator/manual/en/)

### WeChat Mini Game Functions 📲

1. Add Share Function:

    ```javascript
    var id = '' // Image ID approved by MP system
    var url = '' // Image URL approved by MP system
    wx.shareAppMessage({
      imageUrlId: id,
      imageUrl: url
    })
     
    wx.onShareAppMessage(function () {
      return {
        imageUrlId: id,
        imageUrl: url
      }
    })
    ```

2. Add Ad Function:

    ```javascript
    let bannerAd = wx.createBannerAd({
      adUnitId: 'xxxx',
      style: {
        left: 10,
        top: 76,
        width: 320
      }
    })
     
    bannerAd.show()
    ```

### Game Link 🎮

Scan the link below to start the game:

![d4b9a8ad0c9e4e3c8be5031572df27fc](https://github.com/huihuihenqiang/Meow-Game/assets/99072450/f408d414-3146-4923-ab02-2dcceae2d401)


