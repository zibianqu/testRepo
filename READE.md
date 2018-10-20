

# 首页信息获取
----------------------

## 简要描述：

> **首页信息获取**


### 请求URL：
- ` http://xx.com/app/index.php?i=1&c=entry&eid=84 `
- `接口约束：http://xx.com/app/index.php?i=1&c=entry`
  
  
### 请求方式:

> `GET`


### 响应说明：
- `code：100请求返回成功，102参数错误，103请求失败，104请求未找到内容 ，105 请您先完善信息，106请求方式错误`
- `data：返回json格式数据`
- `message：返回请求说明信息`
- `uk：绑定用用户信息`


### 参数：

> **eid** int     必选   模块id

> **act**  string  可选   接口名称


### 返回示例


	{
		"status": true,
		"code": 100,
		"data": {
			"cate": [
				{
					"id": "7",
					"name": "冻干粉",
					"thumb": "http://local.bzwx.com/attachment/"
				},
				{
					"id": "8",
					"name": "原液",
					"thumb": "http://local.bzwx.com/attachment/"
				},
				{
					"id": "9",
					"name": "洁面",
					"thumb": "http://local.bzwx.com/attachment/"
				},
				{
					"id": "10",
					"name": "水乳",
					"thumb": "http://local.bzwx.com/attachment/"
				},
				{
					"id": "11",
					"name": "精华",
					"thumb": "http://local.bzwx.com/attachment/"
				},
				{
					"id": "12",
					"name": "面膜",
					"thumb": "http://local.bzwx.com/attachment/"
				},
				{
					"id": "13",
					"name": "防晒",
					"thumb": "http://local.bzwx.com/attachment/"
				},
				{
					"id": "14",
					"name": "彩妆",
					"thumb": "http://local.bzwx.com/attachment/"
				}
			],
			"slide": [
				{
					"name": "艾司科美",
					"bimg": "http://local.bzwx.com/attachment/images/1/2018/10/EiB8ve8I1iSzAkV1EA5VB1KKBBScbI.png",
					"link": "http://"
				},
				{
					"name": "艾司科美2",
					"bimg": "http://local.bzwx.com/attachment/images/1/2018/10/D3rj93rDRTZaRp3Kdd85AR5kO55nyA.png",
					"link": "http://"
				}
			],
			"adv": [
				{
					"name": "艾司科美",
					"bimg": "http://local.bzwx.com/attachment/images/1/2018/10/EiB8ve8I1iSzAkV1EA5VB1KKBBScbI.png",
					"link": "http://"
				},
				{
					"name": "艾司科美2",
					"bimg": "http://local.bzwx.com/attachment/images/1/2018/10/D3rj93rDRTZaRp3Kdd85AR5kO55nyA.png",
					"link": "http://"
				}
			],
			"expre_cards": [
				{
					"id": "1",
					"name": "艾司美科体验卡",
					"imgurl": "http://local.bzwx.com/attachment/",
					"price": "980.00"
				}
			],
			"member_cards": [
				{
					"id": "5",
					"name": "艾司科美卡",
					"imgurl": "http://local.bzwx.com/attachment/images/1/2018/10/kpKPZRRcK3CzRgMbtD3mgeEUg8vbcr.png",
					"price": "10000.00"
				}
			],
			"goods_essence": [
				{
					"id": "2",
					"title": "清洁保湿润肤乳",
					"thumb": "images/1/2018/10/xDutRD52Z0Jn12nz5NSy8n0r0ZnJq2.png"
				}
			],
			"img_domain ": "http://local.bzwx.com/attachment/"
		},
		"uk": "4D9QE0jn",
		"message": "首页数据信息"
	}


### 返回参数说明:


> **cate:**  首页分类信息，返回数组形式

> **slide:** 首页幻灯片，数组

> **adv:** 广告图片及连接，数组

> **expre_cards：** 体验卡专区

> **member_cards：** 体验卡专区

> **goods_essence:** 精华商品

 **备注** 

- 更多返回错误代码请看首页的错误代码描述


