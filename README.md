# epic7autoBookmark

第七史詩刷商店的小工具  
  
![預覽](https://i.imgur.com/eMp5tMV.png)

## 一、環境
0. windows10 
1. Bluestack  
i. 版本：理論上全版本通用  
ii. 顯示：橫向、1920x1080、320DPI  
iii. 圖形：效能、OpenGL  
2. 第七史詩  
i. 裝置詳細設定和遊戲詳細設定都不勾，可以只勾高級設定，不要用高畫質套件。
3. python3.9.10  
4. config.json  
i. adb_addr填adb路徑  
ii. e7_language填e7裡的語系(繁中: zh-TW, 簡中: zh-CN, 英文: en-US)
  
## 二、使用方式
先將bluestack和第七史詩的設定調整的如上方環境相同。  
adb功能在設定=>進階=>Android調試橋(ADB)，勾選後會看到路徑。  
英文路徑在settings=>Advanced=>Android Debug Bridge(ADB)。  
確認第七史詩語系是不是與config.json裡使用的相同(預設為繁中)。
  
0. 綠色按鈕code > download zip 整包下載後解壓縮放在同一個資料夾下，路徑最好為英數避免有其他問題。
1. 開啟遊戲，進到秘密商店後，畫面會長得像下面這樣。  
  
![預覽](https://i.imgur.com/KxeSpWM.png)  

2. 打開小工具(main.exe)，選擇條件並輸入目標次數，按下開始應該就會自己動惹。  
3. 之前的版本用圖像辨識，而這個版本走的是android adb，已經不會搶滑鼠了，甚至可以縮小放著。  
4. .exe是用pyinstaller包的，有安全疑慮的話可以用資料夾內的main.spec自己打包。  
