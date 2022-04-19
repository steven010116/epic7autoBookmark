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
i. 裝置詳細設定和遊戲詳細設定都不勾，可以只勾高級設定
3. python3.9.10  
4. tesseract  
i. tesseract-ocr-w64 (https://github.com/UB-Mannheim/tesseract/wiki)  
5. config.json  
i. tesseract_path填上方tesseract的安裝路徑(記得處理跳脫字元)  
ii. bluestack_name填模擬器的名稱(視窗名稱)  
  
## 二、使用方式
先將bluestack和第七史詩的設定調整的如上方環境相同。  
並安裝tesseract-w64，然後確認config.json裡的tesseract路徑是不是剛剛安裝的路徑。  
模擬器名稱是bluestack多開管理器裡可以自行命名的那個名稱。  
  
0. 綠色按鈕code > download zip 整包下載後解壓縮放在同一個資料夾下，路徑最好為英數避免有其他問題。
1. 開啟遊戲，進到秘密商店後，收起模擬器右側的擴展欄，畫面會長得像下面這樣。  
  
![預覽](https://i.imgur.com/zvrZS0p.png)  

2. 模擬器須顯示在桌面最上層，且不被任何視窗遮擋，請用視窗化，不要用全螢幕。
3. 打開小工具(main.exe)，選擇條件並輸入目標次數，按下開始應該就會自己動惹。  
.exe是用pyinstaller包的，有安全疑慮的話可以用資料夾內的main.spec自己打包。  
4. 小工具會搶滑鼠，建議洗澡或者吃飯的時候放著跑，不搶滑鼠的得走adb，懶了不想改。  
5. 原本是寫給自己用的，朋友也要用就順便寫了一份教學，不會去解issue，因為我的能動XD  
