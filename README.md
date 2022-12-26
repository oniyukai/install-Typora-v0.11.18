# Typora v0.11.18 安裝說明
這篇會教你如何用正當管道的取得Typora v0.11.18(beta)(Windows)，以及解除它顯示版本過舊無法打開的方法。

## 軟體介紹：
Typora是一款由Abner Lee開發的輕量級Markdown編輯器。而Typora v0.11.18 (beta)是Typora的歷史版本，這個版本是免費版本中的最後更新版，之後正式版(1.0後)要收費。

軟體名稱 | Typora v0.11.18
:-----: | :-----
版本 | v0.11.18 (beta)
功能 | Markdown編輯器
開發者 | Abner Lee
官網 | [typora.io](https://typora.io/)


## 安裝步驟
1. 下載[typora-update-x64-1117.exe](https://web.archive.org/web/20220518163405/https://download.typora.io/windows/typora-update-x64-1117.exe)。
2. 在電腦中安裝"typora-update-x64-1117.exe"，安裝選項建議選擇"Install for all user"。安裝後不用開啟程式。
3. 按下Windows鍵+R鍵，在執行框中輸入`regedit`。
4. 在登錄編輯程式（俗稱"註冊表"）的網址列中輸入`電腦\HKEY_CURRENT_USER\SOFTWARE\Typora`。
5. 在右側的資料夾中找到"Typora"，對那個資料夾點右鍵，點選使用權限。
6. 把所有的群組或使用者的完全控制權限調成拒絕。
7. 按下套用後確定，安裝完成。

> 安裝檔"typora-update-x64-1117.exe"已經在官網無法下載了，原先網址為<https://download.typora.io/windows/typora-update-x64-1117.exe>。但是在[網際網路檔案館](https://archive.org/)有這個安裝檔的備份，教學中的檔案下載連結就是網際網路檔案館的。


## 解除安裝
你會發現你的應用程式庫中沒有他的圖標，因為這個測試版本沒有做完整，所以你需要以下步驟來解除安裝。
1. 打開Typora的程式資料夾。如果安裝時選擇"Install for all user"的人，預設會在"C:\Program Files\Typora"中可以找到。
2. 看到"unins000.exe"，開啟就可以解除安裝了。

經過以上的解除安裝步驟，你仍然可以看到"C:\Users\[使用者名稱]\AppData\Roaming\Typora"與登錄編輯程式中"電腦\HKEY_CURRENT_USER\SOFTWARE\Typora"還在，你可以不理它，或是直接點選刪除，或是再經以下步驟，也可以達到一樣的效果。
1. 在官網[typora.io](https://typora.io/)中下載最新安裝檔。
2. 安裝Typora到你原先安裝歷史版本的資料夾。
3. 下載乾淨解除安裝程式[Geek Uninstaller Free](https://geekuninstaller.com/download)後，用它來解除安裝Typora。
