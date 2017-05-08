# illegal-company-prediction-system - 推測違反勞基法公司

# 使用方式(待編輯)



## 系統主要分為三部分

1. [爬蟲](#crawler爬蟲)
2. [斷詞](#斷詞)
3. [分析](#分析)


### crawler爬蟲

* 使用 python - [scrapy framework](https://github.com/scrapy/scrapy)
* 爬取104公司及Qollie(天眼通)評論資料
* 存入MySQL資料庫


### 斷詞

* 使用中研院斷詞系統



### 分析

* TF-IDF
