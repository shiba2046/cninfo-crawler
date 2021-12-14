# cninfo-crawler
A crawler for cninfo.com.cn

# IPO Info

[IPO Info Home Page](http://www.cninfo.com.cn/new/commonUrl?url=disclosure/ipo/area)


# API URLs

## getMonthTradeDay

`http://www.cninfo.com.cn/data/tradeday/getMonthTradeDay?month=2021-03`
`http://www.cninfo.com.cn/data/tradeday/getMonthTradeDay?month={year}-{month}`


```
	"headers": [
		{
			"name": "Accept",
			"value": "application/json, text/plain, */*"
		},
		{
			"name": "Accept-Encoding",
			"value": "gzip, deflate"
		},
		{
			"name": "Accept-Language",
			"value": "zh-CN,zh;q=0.8,zh-TW;q=0.7,zh-HK;q=0.5,en-US;q=0.3,en;q=0.2"
		},
		{
			"name": "Cache-Control",
			"value": "max-age=0"
		},
		{
			"name": "Connection",
			"value": "keep-alive"
		},
		{
			"name": "Cookie",
			"value": "JSESSIONID=EDA7A6ED5F7F810AB4B180DFAE8E5C67; _sp_id.2141=978a6a76-02f5-4d4d-b1ac-4e2d710f8efb.1614764057.4.1614822496.1614819389.fda499da-b296-4d15-9f5c-dbfc621a9cdd; cninfo_user_browse=605286,9900040546,%E5%90%8C%E5%8A%9B%E6%97%A5%E5%8D%87; routeId=.uc2; _sp_ses.2141=*; insert_cookie=37836164"
		},
		{
			"name": "Host",
			"value": "www.cninfo.com.cn"
		},
		{
			"name": "Referer",
			"value": "http://www.cninfo.com.cn/new/commonUrl?url=disclosure/ipo/area"
		},
		{
			"name": "User-Agent",
			"value": "Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:86.0) Gecko/20100101 Firefox/86.0"
		}
	]
```