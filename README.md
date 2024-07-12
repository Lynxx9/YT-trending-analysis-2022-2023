# Analysis of YouTube Trending Videos of 2022-2023
Youtube為當今最大的影音平台，其中發燒影片可以反映時下廣大觀眾感興趣的影片。因此想分析發燒影片的數據來了解這些發燒影片是否存在著共通點，並以views、likes、comments、publishing hour 這四個面向作為分析的依據。  

## Dataset
截取2022年至2023年美國地區每天更新的發燒影片，共計145196部影片  
[Kaggle-Trending YouTube Video Statistics](https://www.kaggle.com/datasets/datasnaek/youtube-new?select=USvideos.csv)  

註: 附檔"data2022_2023.csv"為前處理後的dataset  

## Extension  
[vidIQ-Install Chrome Extension](https://vidiq.com/extension/)  
安裝vidIQ擴充功能，即可得知影片的"觀看次數成長曲線"

## Execution
先進行pip版本升級並安裝Jupyter Notebook  
  ```bash
  pip3 install --upgrade pip
  ```  
  ```bash
  pip3 install notebook
  ```


再打開cmd 並輸入"jupyter notebook"即可執行  
  ```bash
  jupyter notebook
  ```
