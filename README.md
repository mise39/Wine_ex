# Wine_ex
EX是代表Extreme的版本，這版本是Wine_DLL_Installer_GUI, ZiPatch_gui_python 和 Gal_fix_helper的整合版本。

<img width="1684" height="981" alt="image" src="https://github.com/user-attachments/assets/0732e76d-14cb-4c95-adee-4684b94a5f73" />

# 該版本的出現，意味著以後會集中在這個項目的更新，同時以便各位更容易做對遊戲做修正。

## 注意事項:
1. 本程式由99% Gemini生成 + 1% 人工修正。如有擔心的事項，歡迎審視代碼。
2. 本程式不會用到外來的依賴包，無需pip install XXXXX，一切按照Steam Deck預設的環境下使用。
3. 本程式除了vn_winestuff-main的script安裝lavfilter需要用到網路，其自身是不會使用到網路功能(換言之:程式不會自己更新)。
4. 本人作為業餘人士，未必能夠把安全問題都處理妥當，使用上如有風險，作者不會承擔責任。

## 使用方法:
1. 下載wine_ex.zip並解壓縮  
2. 開啟Konsole指令台。  
3. 輸入指令
```
chmod +x /你的檔案位置/wine_ex.sh
```
4.把這個".sh"加入到非Steam遊戲，然後再執行。  

## *關於Chmod not found的解決方法  
請先konsole輸入
```
passwd
```
設定密碼
然後再輸入  
```
sudo pacman -Sy coreutils
```
Chmod 指令就不會報錯  
