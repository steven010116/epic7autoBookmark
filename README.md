# epic7autoBookmark

第七史詩刷商店的小工具  
  
![預覽](https://i.imgur.com/kAfgbDM.png)

## 一、環境
0. windows10 
1. Bluestack  
i. 版本：5.4.50.1009 64位元  
ii. 顯示：橫向、1920x1080、320DPI  
iii. 圖形：效能、OpenGL  
2. 第七史詩  
i. 只勾高級設定
3. python3.9.10  
4. tesseract  
i. tesseract-ocr-w64 (https://github.com/UB-Mannheim/tesseract/wiki)  
5. config.json  
i. tesseract_path填tesseract的路徑(記得處理跳脫字元)  
ii. bluestack_name填模擬器的名稱(視窗名稱)  
  
## 二、使用方式
0. download zip 整包解壓縮放在同一個資料夾下，路徑最好為英數避免有其他問題。
1. 開啟遊戲，進到秘密商店後，收起模擬器右側的擴展欄，畫面會長得像下面這樣。  
  
![預覽](https://i.imgur.com/zvrZS0p.png)  

2. 模擬器須顯示在桌面最上層，且不被任何視窗遮擋。
3. 打開小工具(main.exe)，選擇條件並輸入目標次數，按下開始應該就會自己動惹。  
4. 小工具會搶滑鼠，建議洗澡或者吃飯的時候放著跑，不搶滑鼠的得走adb，懶了不想改。
5. 原本是寫給自己用的，朋友也要用就順便寫了一份教學，不會去解issue，因為我的能動XD
