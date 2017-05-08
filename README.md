# illegal-company-prediction-system - 推測違反勞基法公司

# 使用方式(待編輯)



## 系統主要分為三部分

1. [爬蟲](#crawler爬蟲)
2. [文字處理](#文字處理)
3. [分析](#分析)


### crawler爬蟲

* 使用 python - [scrapy framework](https://github.com/scrapy/scrapy)
* 爬取104公司及Qollie(天眼通)評論資料
* 存入MySQL資料庫


### 文字處理

* 使用中研院斷詞系統
* 詞頻統計
* 文字的編碼處理


### 分析

* TF
* IDF
