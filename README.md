#CrawlTencentNewsComments
爬取腾讯新闻首页所有新闻及其评论

## 爬取流程
* 爬取新闻正文及其他信息
* 爬取新闻评论

## 测试结果
新闻信息文件`comments_info.json`内容（部分）
```
{"cmtId": "1687646782", "date": "20161227", "newsId": "011065"}
{"cmtId": "1687570251", "date": "20161227", "newsId": "007056"}
{"cmtId": "1687685805", "date": "20161227", "newsId": "012771"}
{"cmtId": "1687587670", "date": "20161227", "newsId": "007947"}
{"cmtId": "1687671711", "date": "20161227", "newsId": "012170"}
{"cmtId": "1687665385", "date": "20161227", "newsId": "011872"}
{"cmtId": "1679979650", "date": "20161222", "newsId": "026418"}
{"cmtId": "2348497395", "date": "20180110", "newsId": "000525"}
{"cmtId": "2348396671", "date": "20180110", "newsId": "000078"}
{"cmtId": "2348273357", "date": "20180109", "newsId": "027113"}
{"cmtId": "2348592476", "date": "20180110", "newsId": "002226"}
{"cmtId": "2166352744", "date": "20171009", "newsId": "039986"}
{"cmtId": "2173173043", "date": "20171013", "newsId": "015252"}
{"cmtId": "2169912017", "date": "20171011", "newsId": "035851"}
{"cmtId": "2166093126", "date": "20171009", "newsId": "028533"}
{"cmtId": "2138224599", "date": "20170921", "newsId": "024045"}
...
```
newsID为011065的新闻对应的评论（部分）
```
"2017年10月11日 11:17:03小伙真是服了你，，，"
"2017年10月10日 21:10:23民告官先打十大板"
"2017年10月10日 10:42:38充分证明了屌丝不懂法"
"2017年10月09日 11:51:49孙洪彬！好样儿的！"
"2017年10月03日 10:28:55看看"
"2017年09月28日 09:25:37法院谁开的？谁给他们开工资？"
"2017年09月27日 21:48:41这个驳得对， 要尊重程序！"
"2017年09月26日 10:33:18shejingbing"
"2017年09月22日 21:24:45应该起诉环保部门，我们凭什么呼吸不合格的空气？环保部门存在的意义是什么？每年拿几十亿的财政工资和补贴干什么？"
"2017年09月22日 17:28:33这个新闻都是去年的，咋一直放首页？腾讯编辑也太懒惰了吧？"
"2017年09月22日 08:45:06合理诉求，无理驳回，神判决"
"2017年09月20日 11:31:17看看"
"2017年09月19日 01:49:59简直搞笑"
"2017年09月18日 09:44:14他也知道告不赢，提高一下自己的知名度罢了。"
"2017年09月14日 16:13:25什么人都有，，，"
"2017年09月06日 15:11:23僵尸打开他的大脑失望的走了，屎壳郎兴奋的跑了过来。"
"2017年09月05日 14:43:55虽然钱少，但问题值得重视"
"2017年09月01日 13:31:57正大于法，还是法大于正~~~用脚趾头想想就明白了~~~"

```
