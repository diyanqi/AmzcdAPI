# AmzcdAPI 使用指南

> 本API只做学习使用，不含任何商业推广。

> 所有API条目按开发顺序先后排列。
>
> API url 的统一命名方式为：`https://api.amzcd.top/名称/版本/具体内容`

## bilibili

### 首页视频 topVideos

- url：`https://api.amzcd.top/bilibili/v1/topVideos`。
- 请求方式：`POST`,`GET`。
- 参数：不带参。
- 返回值：JSON字符串。
- 返回示例：

```json
{"code":0,"message":"0","ttl":1,"data":{"item":[{"id":546724247,"bvid":"BV14q4y1W7dS","goto":"av","uri":"https://www.bilibili.com/video/BV14q4y1W7dS","pic":"http://i2.hdslb.com/bfs/archive/a46244756f1fc48f0a7a1c1608fd01c7183c5458.jpg","title":"【A-soul】真心为你.","duration":666,"owner":{"mid":36704260,"name":"健康死亡","face":"http://i1.hdslb.com/bfs/face/9a3be02f5b017ead087d22abbcc645650105b835.jpg"},"stat":{"view":29525},"av_feature":null},{"id":889153496,"bvid":"BV1MK4y1u7nX","goto":"av","uri":"https://www.bilibili.com/video/BV1MK4y1u7nX","pic":"http://i1.hdslb.com/bfs/archive/bdbe85a2472a61085c311ac7397de683e5bbfeef.jpg","title":"【跑团】长生村之谜19 | 完结","duration":1651,"owner":{"mid":162265056,"name":"整天摸鱼的三日坊主","face":"http://i0.hdslb.com/bfs/face/3d54e071202bd1f21ed0142a3ca2397775f7f75d.jpg"},"stat":{"view":55646},"av_feature":null},{"id":546658859,"bvid":"BV1Tq4y1W7vM","goto":"av","uri":"https://www.bilibili.com/video/BV1Tq4y1W7vM","pic":"http://i0.hdslb.com/bfs/archive/a879c45b1fdbcbe7b95f7e9296bb98c41c55358c.jpg","title":"【STN快报第五季46】言出法随，大口四方","duration":1416,"owner":{"mid":7349,"name":"STN工作室","face":"http://i2.hdslb.com/bfs/face/5d0166221aae4b1673f62679df62bdd0f6a64a11.jpg"},"stat":{"view":782610},"av_feature":null},{"id":674294080,"bvid":"BV1bU4y1n7Nx","goto":"av","uri":"https://www.bilibili.com/video/BV1bU4y1n7Nx","pic":"http://i2.hdslb.com/bfs/archive/393267e3ab8b0251d26ce94a90de51495802aa5e.jpg","title":"【洛天依·言和原创曲】双星伴生【周存投稿九周年/PV付】","duration":198,"owner":{"mid":341368,"name":"JUSF周存","face":"http://i1.hdslb.com/bfs/face/4130937f882d03bbf8162832e6f20ff00b639332.jpg"},"stat":{"view":17781},"av_feature":null},{"id":206701173,"bvid":"BV1dh41167Rb","goto":"av","uri":"https://www.bilibili.com/video/BV1dh41167Rb","pic":"http://i2.hdslb.com/bfs/archive/0c922d79ec10509ea441c3e60fc709e3db92c072.jpg","title":"【神经病剧场】被 玩 坏 的 泛 哥 哥 ！","duration":409,"owner":{"mid":63231,"name":"泛式","face":"http://i0.hdslb.com/bfs/face/5f60d345059b82f0878984d9f9133f45b33b82be.jpg"},"stat":{"view":606049},"av_feature":null},{"id":291805028,"bvid":"BV15f4y157Ci","goto":"av","uri":"https://www.bilibili.com/video/BV15f4y157Ci","pic":"http://i2.hdslb.com/bfs/archive/bf85ff5802354d4fecf37fc2090002348da3432c.jpg","title":"一舰vs一国 真碧蓝无双开场cg","duration":78,"owner":{"mid":27380,"name":"钻头V会长","face":"http://i2.hdslb.com/bfs/face/a776a13b293910dd1cbd0fd2147e63197b32ea32.jpg"},"stat":{"view":36169},"av_feature":null},{"id":631769052,"bvid":"BV14b4y167if","goto":"av","uri":"https://www.bilibili.com/video/BV14b4y167if","pic":"http://i0.hdslb.com/bfs/archive/53a326f1ee82e465b960b17346e5f66105b479b9.jpg","title":"三句话把我骗到了bilibili【九重紫】","duration":91,"owner":{"mid":225347042,"name":"九重紫Official","face":"http://i2.hdslb.com/bfs/face/6384d37272710b194d182abe54384b09b88d6719.jpg"},"stat":{"view":17151},"av_feature":null},{"id":334141352,"bvid":"BV1aw411d7o7","goto":"av","uri":"https://www.bilibili.com/video/BV1aw411d7o7","pic":"http://i0.hdslb.com/bfs/archive/59b292e19991d1686f25a3cbe945c64ab93ae6f9.jpg","title":"太悲壮！血战至最后一人！《亮剑》P3","duration":2007,"owner":{"mid":927587,"name":"木鱼水心","face":"http://i2.hdslb.com/bfs/face/e922d9dc09a2d21f1400ad0f02f75ecf1b3575c8.jpg"},"stat":{"view":1531358},"av_feature":null},{"id":761792938,"bvid":"BV1D64y1s7fJ","goto":"av","uri":"https://www.bilibili.com/video/BV1D64y1s7fJ","pic":"http://i1.hdslb.com/bfs/archive/6d0b9ab93a09a857463ee014de790e64f51aaeed.jpg","title":"【罗小黑战记】显微镜下的罗小黑之劝学篇（39集）","duration":1033,"owner":{"mid":25396635,"name":"澂-笛","face":"http://i0.hdslb.com/bfs/face/7af4c7a940f490491c8cd479bb026863cf6c87b9.jpg"},"stat":{"view":57034},"av_feature":null},{"id":631644580,"bvid":"BV1hb4y1k7Tk","goto":"av","uri":"https://www.bilibili.com/video/BV1hb4y1k7Tk","pic":"http://i0.hdslb.com/bfs/archive/56667c7fe44ecb58d657ad8a630fbdbfd8a42825.jpg","title":"OP画面拉胯？那修改亿点点再看看！【特利迦奥特曼】","duration":274,"owner":{"mid":7799336,"name":"Saydontbob","face":"http://i2.hdslb.com/bfs/face/4d1436e11665762db8abbde8a4903a41b25b480d.jpg"},"stat":{"view":395551},"av_feature":null},{"id":761714548,"bvid":"BV1f64y147xe","goto":"av","uri":"https://www.bilibili.com/video/BV1f64y147xe","pic":"http://i2.hdslb.com/bfs/archive/65098a1f0df24fb1fda7bb8ee5c5dea2cbed7e69.jpg","title":"逐梦动画圈！中国二维动画公司求职指南","duration":952,"owner":{"mid":69334,"name":"睡觉人project","face":"http://i1.hdslb.com/bfs/face/c12121d1235b315467d5a71dba3dc71e25e6671d.jpg"},"stat":{"view":14502},"av_feature":null},{"id":504151003,"bvid":"BV11g411T7u5","goto":"av","uri":"https://www.bilibili.com/video/BV11g411T7u5","pic":"http://i2.hdslb.com/bfs/archive/840dabb171f78c64660d6984c8a537f11af5bd23.jpg","title":"【新番新吐槽】社畜穿越成社畜？请停止你的套娃行为！","duration":594,"owner":{"mid":404888281,"name":"在下三少啦","face":"http://i1.hdslb.com/bfs/face/c6d254dacc6d83b5fb3f1f200ba6ea81288af54c.jpg"},"stat":{"view":42822},"av_feature":null},{"id":206726050,"bvid":"BV19h41167ay","goto":"av","uri":"https://www.bilibili.com/video/BV19h41167ay","pic":"http://i0.hdslb.com/bfs/archive/bae33ef0912156e66009c7d4d766df92d1f71f3a.jpg","title":"【泠鸢/hanser】《时光代理人》ED-翻唱，红眼睛和金眼睛的人哦都小心点","duration":184,"owner":{"mid":282994,"name":"泠鸢yousa","face":"http://i1.hdslb.com/bfs/face/28f95c383f2805dbed32e93007c91ccfda28775f.jpg"},"stat":{"view":542747},"av_feature":null},{"id":461685618,"bvid":"BV1LL411H7q2","goto":"av","uri":"https://www.bilibili.com/video/BV1LL411H7q2","pic":"http://i0.hdslb.com/bfs/archive/52fcb8841824fa405ba5888e9dcbd153353355c6.jpg","title":"猫咪肠粉一口一个","duration":243,"owner":{"mid":404216060,"name":"幾加乘","face":"http://i2.hdslb.com/bfs/face/3e121cd62f9ec860ec7640fea1e19c15a9dd370c.jpg"},"stat":{"view":901490},"av_feature":null},{"id":461734927,"bvid":"BV16L411H7tw","goto":"av","uri":"https://www.bilibili.com/video/BV16L411H7tw","pic":"http://i0.hdslb.com/bfs/archive/e0bb20f47b475a945db45bbf452a1610ead34f74.jpg","title":"剧TOP：报仇点到为止，报恩家破人亡，港剧巅峰《大时代》全解读（第三回）","duration":1972,"owner":{"mid":17819768,"name":"电影最TOP","face":"http://i2.hdslb.com/bfs/face/6b2ade215ea603b495648875c925172a863d16d4.jpg"},"stat":{"view":394599},"av_feature":null},{"id":846696670,"bvid":"BV1f54y1n7C8","goto":"av","uri":"https://www.bilibili.com/video/BV1f54y1n7C8","pic":"http://i1.hdslb.com/bfs/archive/bad67d54f961c6faafc7e88d920b970f292a0e79.jpg","title":"【微缩场景】dota2全地图制作第三期","duration":1145,"owner":{"mid":332038975,"name":"天梯一分选手","face":"http://i1.hdslb.com/bfs/face/835e763ff8f7e31b18ff53b7df265292c3fd64d4.jpg"},"stat":{"view":136881},"av_feature":null},{"id":504150024,"bvid":"BV1yg411T7fB","goto":"av","uri":"https://www.bilibili.com/video/BV1yg411T7fB","pic":"http://i2.hdslb.com/bfs/archive/abaab75c5d142a2e7a41f3b0a8539ec102e1e062.jpg","title":"“如果高考也能拼夕夕...”","duration":171,"owner":{"mid":341069816,"name":"刘拖地","face":"http://i2.hdslb.com/bfs/face/c5c343cff2a87ec2c88ba5cc6bbc516e2fd157b3.jpg"},"stat":{"view":361884},"av_feature":null},{"id":931744127,"bvid":"BV1qM4y1K7jq","goto":"av","uri":"https://www.bilibili.com/video/BV1qM4y1K7jq","pic":"http://i0.hdslb.com/bfs/archive/ca84a4a77aa63986b027278f06bd4b2423315ad3.jpg","title":"个人毕业动画作品《赤星》","duration":330,"owner":{"mid":41790370,"name":"icebirdlancet","face":"http://i1.hdslb.com/bfs/face/bde325875cdfdf5140a8a2a8c0abf20094866ac2.jpg"},"stat":{"view":987330},"av_feature":null},{"id":974126992,"bvid":"BV1c44y1B7Ya","goto":"av","uri":"https://www.bilibili.com/video/BV1c44y1B7Ya","pic":"http://i0.hdslb.com/bfs/archive/7603c390a465fcc81e37a1d65a8d6df33351ef23.jpg","title":"韩国文化输出有多强 | 有轶见","duration":799,"owner":{"mid":23008074,"name":"有轶见的Kris","face":"http://i0.hdslb.com/bfs/face/3b7ce33debc6a27c05e68ed6677618a6a9b5c6f8.jpg"},"stat":{"view":577537},"av_feature":null},{"id":546670035,"bvid":"BV1Hq4y1W7MG","goto":"av","uri":"https://www.bilibili.com/video/BV1Hq4y1W7MG","pic":"http://i0.hdslb.com/bfs/archive/d51168fdbce04f27d6ba97524e98668900111678.jpg","title":"【马又】不用左键也能通关MC！","duration":2059,"owner":{"mid":39468669,"name":"马又SYQ","face":"http://i0.hdslb.com/bfs/face/db9f34a262cfe29c9c862ad113190b2ec2ba5f4a.jpg"},"stat":{"view":67687},"av_feature":null},{"id":974193287,"bvid":"BV1q44y127W5","goto":"av","uri":"https://www.bilibili.com/video/BV1q44y127W5","pic":"http://i2.hdslb.com/bfs/archive/b35aab120b14c4ea0743f1da1563d01b66298bf5.jpg","title":"【闻香识】外挂也硬杀！一命通关20杀复活岛双锤骷髅海复刻计划成功！","duration":819,"owner":{"mid":193584,"name":"闻香识","face":"http://i2.hdslb.com/bfs/face/0bfa1ba986146fc9cda19baecf165dee291f9109.jpg"},"stat":{"view":79075},"av_feature":null},{"id":546720174,"bvid":"BV1xq4y1W7CR","goto":"av","uri":"https://www.bilibili.com/video/BV1xq4y1W7CR","pic":"http://i0.hdslb.com/bfs/archive/b0726670bb5f8bf9f0f32199a8bf294af6da4d79.jpg","title":"【阴阳师】这样最划算！！全新活动“罪业回舞”数据化教你怎么做收益最大化！","duration":693,"owner":{"mid":9993190,"name":"居居魅","face":"http://i1.hdslb.com/bfs/face/f56a52ad250037896b093fd9d848bec228e5861c.jpg"},"stat":{"view":56399},"av_feature":null},{"id":376703356,"bvid":"BV1xo4y1D7C6","goto":"av","uri":"https://www.bilibili.com/video/BV1xo4y1D7C6","pic":"http://i1.hdslb.com/bfs/archive/0ae1798786671753f9f7cbd7c9a1f3c0b6809c9d.jpg","title":"防火女动作修改跳极乐净土","duration":441,"owner":{"mid":22255812,"name":"反叛的银猫","face":"http://i0.hdslb.com/bfs/face/57ea218f44c5b1d496928a518010ee8fa39540ca.jpg"},"stat":{"view":298369},"av_feature":null},{"id":974162001,"bvid":"BV1x44y1279d","goto":"av","uri":"https://www.bilibili.com/video/BV1x44y1279d","pic":"http://i0.hdslb.com/bfs/archive/0d61d991eefd4bdeec8d7c334eeb44fd5e0f9aa9.jpg","title":"【原神】我好像推测出了什么不得了的东西………………","duration":778,"owner":{"mid":1074545099,"name":"甜甜叫花鸡","face":"http://i2.hdslb.com/bfs/face/99eac3be1bba7cf1a3fd2f0e3dffee95639a34be.jpg"},"stat":{"view":478638},"av_feature":null},{"id":589361136,"bvid":"BV13q4y1X7VH","goto":"av","uri":"https://www.bilibili.com/video/BV13q4y1X7VH","pic":"http://i0.hdslb.com/bfs/archive/d4114ab6a169de7b3921ac84e5184f05650cc00b.jpg","title":"宠粉大师：“我再惯你们一回，削个俊哲过1周年？”","duration":138,"owner":{"mid":352248648,"name":"三毛水果艺术","face":"http://i0.hdslb.com/bfs/face/6d4af542204dbaa87a786cb7c6aa3fca63bee5bd.jpg"},"stat":{"view":68611},"av_feature":null},{"id":889238519,"bvid":"BV1JP4y147xz","goto":"av","uri":"https://www.bilibili.com/video/BV1JP4y147xz","pic":"http://i2.hdslb.com/bfs/archive/aa9022fe5ef88be6ddec2be7cfec0a7601eb8598.jpg","title":"【翻唱】采石 Short ver-万能青年旅店（Cpt.Ahab Ver）","duration":291,"owner":{"mid":427275473,"name":"亚哈Ahab_Channel","face":"http://i2.hdslb.com/bfs/face/547e266758c6e7498d04d7cbdd69ff73ce2d47dc.jpg"},"stat":{"view":12997},"av_feature":null},{"id":674216722,"bvid":"BV13U4y1G77X","goto":"av","uri":"https://www.bilibili.com/video/BV13U4y1G77X","pic":"http://i2.hdslb.com/bfs/archive/0c34268c281fecb60d661e14c75806ce0feb0736.jpg","title":"【神楽めあ】完全放棄宣言【入驻B站三周年纪念】【翻唱/PV付】","duration":267,"owner":{"mid":349991143,"name":"神楽Mea_Official","face":"http://i1.hdslb.com/bfs/face/54d113501f56b165f03ebc96965c43bed57b6bc3.jpg"},"stat":{"view":52663},"av_feature":null},{"id":804223703,"bvid":"BV1ty4y1T7aE","goto":"av","uri":"https://www.bilibili.com/video/BV1ty4y1T7aE","pic":"http://i1.hdslb.com/bfs/archive/5b8444f4bf3f4297619514bb8bed227964a14af2.jpg","title":"《无事发生》全曲试听 | 三无Marblue首张实体专辑","duration":434,"owner":{"mid":284120,"name":"三无Marblue","face":"http://i2.hdslb.com/bfs/face/d38f799fc0ae99efd60985306c7c15e0e1ecacb1.jpg"},"stat":{"view":217880},"av_feature":null},{"id":674161705,"bvid":"BV1yU4y137UZ","goto":"av","uri":"https://www.bilibili.com/video/BV1yU4y137UZ","pic":"http://i1.hdslb.com/bfs/archive/868616107c69b4e00a1a72daebec0a067f2fab3b.jpg","title":"【神作赏析】超越官方！明日方舟超强自制动画《最后的 进军》逐 帧 赏 析！","duration":1319,"owner":{"mid":153298,"name":"司徒一辰","face":"http://i1.hdslb.com/bfs/face/253513c112001d2c04048839b53e30b8e61380ab.jpg"},"stat":{"view":292161},"av_feature":null},{"id":674151871,"bvid":"BV1DU4y137JC","goto":"av","uri":"https://www.bilibili.com/video/BV1DU4y137JC","pic":"http://i1.hdslb.com/bfs/archive/039091e21a77d5f1d595a1f37358fb96b91c76c8.jpg","title":"【花谱】日文翻唱《革命バーチャルリアリティ/革命虚拟现实》","duration":225,"owner":{"mid":488970166,"name":"花谱_kaf","face":"http://i1.hdslb.com/bfs/face/c1e5ead708dd3e4df77fc6b6ff1a8bda36df71dd.jpg"},"stat":{"view":21411},"av_feature":null}],"user_feature":null,"abtest":{"group":"a"}}}
```

### 获取视频直链 videoUrl

 - url：`https://api.amzcd.top/bilibili/v1/videoUrl?vid=视频号`。

 - 请求方式：`GET`。

 - 参数：

   - `vid`：视频号，比如`https://www.bilibili.com/video/BV1Yy4y1t7DH`的`vid`就是`BV1Yy4y1t7DH`。

 - 返回值：字符串。

 - 返回示例：

   ```bash
   https://upos-sz-mirrorkodo.bilivideo.com/upgcxcode/09/43/368344309/368344309_nb2-1-16.mp4?e=ig8euxZM2rNcNbdlhoNvNC8BqJIzNbfq9rVEuxTEnE8L5F6VnEsSTx0vkX8fqJeYTj_lta53NCM=&uipk=5&nbs=1&deadline=1626699187&gen=playurlv2&os=kodobv&oi=1943365314&trid=7b95e46b83fb4b1fa03e9c5bb87257afh&platform=html5&upsig=88e0cf026142ea2dabcacad1bd8c8e57&uparams=e,uipk,nbs,deadline,gen,os,oi,trid,platform&mid=0&logo=80000000
   ```

## 翻译

### 谷歌翻译 GoogleTranslate

 - url：`https://api.amzcd.top/translate/v1/google?source=源文本&from=源语言简码&to=目标语言简码`。

 - 请求方式：`GET`。

 - 参数：

   - `source`：源文本，即翻译前的文本。
   - `from`：源语言简码，例如英语为`en`。
   - `to`：目标语言简码。

 - 返回值：字符串。

 - 返回示例：

   ```bash
   早上好。
   ```

### 有道翻译 YoudaoTranslate

 - url：`https://api.amzcd.top/translate/v1/youdao?source=源文本`。

 - 请求方式：`GET`。

 - 参数：

   - `source`：源文本，即翻译前的文本。该API只能实现中文英文互翻译。

 - 返回值：字符串。

 - 返回示例：

   ```bash
   晚上好。
   ```

### DeepL翻译 DeepLTranslate

 - url：`https://api.amzcd.top/translate/v1/deepl?source=源文本&from=源语言简码&to=目标语言简码`。

 - 请求方式：`GET`。

 - 参数：

   - `source`：源文本，即翻译前的文本。
   - `from`：源语言简码，例如英语为`en`。
   - `to`：目标语言简码。

 - 返回值：字符串。

 - 返回示例：

   ```bash
   Welcome!
   ```

## 基本

- TIP：本功能主要为AppCraft所作，因其缺少基本功能。

### 时间 Time

 - url：`https://api.amzcd.top/simple/v1/time`。

 - 请求方式：`GET`。

 - 参数：无。

 - 返回值：字符串。

 - 返回示例：

   ```bash
   Wed Jul 21 10:47:10 2021
   ```

## 图片

- TIP：为节约服务器资源，本功能会将**大部分**图片资源重定向到`https://static.amcd.top`上。

## 随机东方二次元壁纸 

- url：`https://api.amzcd.top/pic/v1/randpic/eastern?size=图片尺寸`。

- 请求方式：`GET`。

- 参数：

  - `size`：图片的尺寸，有`banner`（横幅）和`vertical`（竖版）两种类型。

- 返回值：301重定向。

- 返回示例：

  ```
  301重定向：https://static.amzcd.top/eastern/banner1.JPEG
  ```

## 必应每日一图

- url：`https://api.amzcd.top/pic/v1/bingimg`。

- 请求方式：`GET`。

- 参数：无

- 返回值：301重定向。

- 返回示例：

  ```
  301重定向：https://bing.com//th?id=OHR.VermilionLakes_ZH-CN3446257764_1920x1080.jpg&rf=LaDigue_1920x1080.jpg&pid=hp
  ```

