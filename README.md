# Missle-Defense

![S__37404859_0](https://github.com/Anouo1023/Missle-Defense/assets/134196295/b7dbc696-2d45-4fd0-bf82-0bc2ad503d6b)
 <p> 
2023 國中七年級數理資優資訊專題實作 - 飛彈雷達防禦系統程式碼 - 開源專案
 </p> <p> 
以下相關程式，部分為網路參考而來，我將盡力提供其原始來源。
 </p> <p> 
以下相關硬件，部分為網路購買，我將儘力提供其原始來源。
 </p> <p> 

# 如何開始



1.確定要如何進行操控(粗體為我們所採用的方案)

  

- 像是雷達要使用**Arduino**還是樹梅派(改寫Python)

- 砲塔要使用C++或是**C#**
- 因此我們以下有使用到的程式碼僅針對用Arduino寫的夾物車

2.先認識會使用到的控制面板們

  

-  **Arduino UNO跟MEGA**為最有可能使用的操控方案，UNO的腳位較少但其對電腦及其他電路板驅動較好，MEGA腳位較多但因為幾乎都是非公版所以其對電腦及其他版的驅動性較差
3.當雷達來了之後，使用Arduino官方軟體以閱讀並編輯程式碼(廠商已隨商品附贈程式碼)
![ide-7](https://github.com/Anouo1023/Missle-Defense/assets/134196295/63d730d0-4187-4a43-ba0c-eb48c41f817c)

## 我們所使用的控制原理

當雷達掃描到物體後，面板呈現紅色，傳給筆電後顯示。
 </p> <p> 
筆電獲得到資訊後，再傳給砲塔，並攻擊目標物。
 </p> <p> 
原理圖如下:
  <p>
https://github.com/Anouo1023/Missile-Defense/assets/134196295/8b08ef6e-0f98-4446-ba1f-eac7654becce


  ## 採買電子材料會用到的店家

  

1. **ebay**
 </p> <p> 
2. 露天市集
 </p><img width="659" alt="截圖_2023-07-23_下午11 24 48" src="https://github.com/Anouo1023/Missile-Defense/assets/134196295/9b452a9b-856a-43bd-a56a-5ff164347346">

 <p>
 ![露天版圖](https://github.com/Anouo1023/Missile-Defense/assets/134196295/69787ca6-2d1d-498c-96ea-63ed0a6556ec)


# Arduino原始碼
<p> Arduino雷達
 </p> <p> 
<p> 砲塔(DreemCheeky)
