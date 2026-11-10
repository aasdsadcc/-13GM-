<img width="1918" height="1039" alt="0a7436ffe2c7f87e232abe68a619cc87" src="https://github.com/user-attachments/assets/d3462b3c-709f-473d-954a-865e9958a458" />
1.遇到同步中按F8即可退出，原理是通过断开steamlobby的房间做到的，这样就不会出现游戏无限卡死的状态
2.同时面板增加UDP通道预热，5MS的心跳UDP，让游戏同步更加快速，几乎秒同步游戏
3.game.exe修改为可靠传输，大幅度优化丢包概率，游戏同步卡死的频率更低
