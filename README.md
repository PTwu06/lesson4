# Lesson4_手繪數字模型辨識網頁:satisfied:
![image](https://github.com/PTwu06/lesson4/blob/master/homepage%E6%88%AA%E5%9C%96small.png)
* __此專案中，透過訓練一個Mnist數字分類模型並將其轉換成onnx格式，即可自行於網頁畫布繪畫，並於console中查看數字辨識的過程。__
* __功能提供:__
  * 畫筆顏色更換、畫布Reset
  * BGM list循環撥放(共四首)
---
>## 網頁  <sub>(homepae 資料夾)</sub>
>>__使網頁於本地運行__
>>* 於終端機輸入 `npx serve`
>>>:warning: :若於運行 `html` 時出現如下錯誤，以致 __看不見繪圖軌跡__ ，請於 VS code   
安裝 `Live server` 插件， __以Live server運行html__。
![image](https://github.com/PTwu06/lesson4/blob/master/html_warning.png)
>## Mnist 模型訓練與安裝  <sub>(model_and_train 資料夾)</sub>
>* 請參照 `model_and_train` 資料夾中的 `README.md` 操作。
