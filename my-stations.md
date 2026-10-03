# 我的网络电台列表

> ### 怎么填
>
> 1. 每行一个电台，格式固定为：**`- 电台名称 | 音频流地址`**
>    名称和地址中间用竖线 `|` 分隔，前后空格随意。
> 2. 把 `【填网址】` 替换成真正的音频流直链，必须以 `http://` 或 `https://` 开头。
> 3. **没填地址的行会被自动跳过**，所以你可以只填一部分，填一行算一行，不影响其他行。
> 4. `## 地区名` 是分组标题，会显示在左侧栏。想改分组名就直接改标题文字，想加分组就自己加一行 `## xxx`。
> 5. 填完存成 **UTF-8** 编码，上传到你的 GitHub 仓库。
> 6. 在收音机右上角「齿轮」里粘贴这个文件的 **raw 链接**（`https://raw.githubusercontent.com/...`）。
>
> ### 音频流地址从哪来
>
> - 打开电台官网点「在线收听」，按 F12 打开开发者工具 → Network → 筛选 `media`，找到真正的流地址。
> - 常见后缀：`.mp3`、`.aac`、`.ogg`、`.m3u8`（HLS）、`/stream`、`:8000/xxx`（Icecast / Shoutcast）。
> - **不要填网页地址**（如 `https://www.xxx.com/radio`）——那是一个网页而不是音频流，播放器会提示「无法播放」。
> - 找公开电台可参考：radio-browser.info、streamurl.link。
>
> ### 支持的几种写法（任选，效果一样）
>
> - `- 电台名称 | https://stream.example.com/xx.mp3`　　竖线分隔（推荐，最清楚）
> - `- [电台名称](https://stream.example.com/xx.mp3)`　　Markdown 链接写法
> - `- 电台名称 https://stream.example.com/xx.mp3`　　空格分隔
> - `- https://stream.example.com/xx.mp3`　　只有地址，名称自动取域名
> - `**地区名**` 单独一行，等价于 `## 地区名`
>
> 注：代码块（三个反引号包裹）和引用块（`>` 开头）里的内容会被忽略，可以放心写笔记。

## 中国大陆

### 珠海

- 珠海斗门电台 FM92.8 | https://lhttp.qingting.fm/live/15318432/64k.mp3
- 珠海电台先锋951 FM95.1 | https://lhttp.qingting.fm/live/1274/64k.mp3
- 珠海电台活力915 FM91.5 | https://lhttp.qingting.fm/live/5021725/64k.mp3
### 南宁

- 广西广播电视台经济广播 | https://lhttp.qingting.fm/live/1754/64k.mp3
- 广西广播电视台综合广播 | https://lhttp.qingting.fm/live/1753/64k.mp3
- 广西广播电视台音乐广播 | https://lhttp.qingting.fm/live/4875/64k.mp3
- 广西广播电视台私家车广播 | https://lhttp.qingting.fm/live/1756/64k.mp3
- 广西广播电视台交通广播 | https://lhttp.qingting.fm/live/1758/64k.mp3
- 广西北部湾之声 | https://lhttp.qingting.fm/live/1757/64k.mp3
### 深圳

- 广东电台优悦广播 FM105.7 | https://lhttp.qingting.fm/live/470/64k.mp3
- 深圳交通频率 FM106.2 | https://lhttp.qingting.fm/live/1272/64k.mp3
- 深圳先锋898 FM89.8 | https://lhttp.qingting.fm/live/1270/64k.mp3
- 深圳生活广播 FM94.2 | https://lhttp.qingting.fm/live/1273/64k.mp3
- 深圳飞扬971 FM97.1 | https://lhttp.qingting.fm/live/1271/64k.mp3
- 龙岗广播 FM99.1 | https://lhttp.qingting.fm/live/20160/64k.mp3
### 昆明

- 云南广播电视台调频广播 | https://lhttp.qingting.fm/live/20139/64k.mp3
- 云南广播电视台音乐之声 | https://lhttp.qingting.fm/live/1929/64k.mp3
- 云南广播电视台新闻广播 | https://lhttp.qingting.fm/live/1926/64k.mp3
- 云南广播电视台少数民族语言广播 | https://lhttp.qingting.fm/live/1933/64k.mp3
- 云南广播电视台交通之声 | https://lhttp.qingting.fm/live/1928/64k.mp3
- 昆明汽车广播 | https://lhttp.qtfm.cn/live/1936/64k.mp3
### 乌鲁木齐

- 新疆交通广播 FM92.9 | https://lhttp.qingting.fm/live/1909/64k.mp3
- 新疆广播电视台哈萨克语广播 FM98.2 | https://lhttp.qingting.fm/live/1908/64k.mp3
- 新疆广播电视台新闻综合广播 FM96.1 | https://lhttp.qingting.fm/live/1902/64k.mp3
- 新疆广播电视台维吾尔语广播 FM88.9 | https://lhttp.qingting.fm/live/5022688/64k.mp3
### 长沙

- 幸福广播 FM88.6 | https://lhttp.qingting.fm/live/20847/64k.mp3
### 青岛

- 青岛广播电视台音乐体育广播 | https://lhttp.qingting.fm/live/1677/64k.mp3
- 青岛广播电视台私家车广播 | https://lhttp.qingting.fm/live/1675/64k.mp3
- 青岛广播电视台交通广播 | https://lhttp.qingting.fm/live/1676/64k.mp3
### 海口

- 海南广播电视台民生广播 | https://lhttp.qingting.fm/live/21243/64k.mp3
- 海南广播电视台旅游广播 | https://lhttp.qingting.fm/live/1862/64k.mp3
- 海南广播电视台音乐广播 | https://lhttp.qingting.fm/live/4878/64k.mp3
### 哈尔滨

- 哈尔滨音乐广播 FM90.9 | https://lhttp.qingting.fm/live/839/64k.mp3
- 哈尔滨文艺广播 FM98.4 | https://lhttp.qtfm.cn/live/20083/64k.mp3
- 黑龙江交通广播 FM99.8 | https://lhttp.qingting.fm/live/4973/64k.mp3
### 武汉

- 湖北广播电视台经济广播 | https://lhttp.qingting.fm/live/1295/64k.mp3
- 湖北广播电视台音乐广播 | https://lhttp.qingting.fm/live/1289/64k.mp3
- 湖北广播电视台新闻综合广播 | https://lhttp.qingting.fm/live/1303/64k.mp3
### 娄底

- 娄底综合广播 FM107.2 | https://lhttp.qingting.fm/live/21213/64k.mp3
### 杭州

- 浙江广播电视台交通广播 | https://lhttp.qingting.fm/live/4522/64k.mp3
- 浙江广播电视台之声 | https://lhttp.qingting.fm/live/4518/64k.mp3
### 长春

- 长春 UFM 88.0 | https://lhttp.qingting.fm/live/4850/64k.mp3
- 长春新闻广播 FM88.9 | https://lhttp.qingting.fm/live/5013/64k.mp3
### 云浮

- 云浮电台交通音乐广播 FM96.4 | https://lhttp.qingting.fm/live/5022441/64k.mp3
- 云浮电台综合广播 FM100.6 | https://lhttp.qingting.fm/live/5022442/64k.mp3
### 中山

- 中山电台快乐888 FM88.8 | https://lhttp.qingting.fm/live/1278/64k.mp3
- 中山电台新锐967 FM96.7 | https://lhttp.qingting.fm/live/1277/64k.mp3
### 衡阳

- 衡阳综合广播 FM98.9 | https://lhttp.qingting.fm/live/15318386/64k.mp3
### 梅州

- 梅州电台新闻台 FM94.8 | https://lhttp.qingting.fm/live/1257/64k.mp3
### 福州

- 福建广播电视台新闻综合广播 | https://lhttp.qingting.fm/live/1731/64k.mp3
### 大理

- 大理雪莱与斯宾诺莎电台 | https://s2.radio.co/sec5fa6199/listen
### 邵阳

- 邵阳综合广播 FM95.4 | https://lhttp.qingting.fm/live/20148/64k.mp3
### 清远

- 清远综合广播 FM88.7 | https://lhttp.qingting.fm/live/15318668/64k.mp3
### 汕头

- 澄海人民广播电台 FM100.5 | https://lhttp.qingting.fm/live/5022439/64k.mp3
### 沈阳

- 辽宁经典音乐广播 FM95.9 | https://lhttp.qingting.fm/live/20021/64k.mp3
### 湘潭

- 湘潭应急广播 FM104.2 | https://lhttp.qingting.fm/live/21269/64k.mp3
### 常德

- 常德新闻广播 | https://lhttp.qingting.fm/live/15318208/64k.mp3
### 盐城

- 大丰人民广播电台 FM95.1 | https://lhttp.qingting.fm/live/20211708/64k.mp3
### 阳江

- 阳江旅游环保广播 FM89.5 | https://lhttp.qingting.fm/live/15318428/64k.mp3
### 岳阳

- 岳阳经济广播 FM104.5 | https://lhttp.qingting.fm/live/5022391/64k.mp3
### 湛江

- 湛江经济广播 FM95.1 | https://lhttp.qingting.fm/live/5069/64k.mp3
### 南京

- 南京音乐广播 | https://lhttp.qingting.fm/live/4963/64k.mp3
### 郴州

- 郴州综合广播 FM99.2 | https://lhttp.qingting.fm/live/20489/64k.mp3
### 北京

- 北京欢乐广播 FM87.6 | https://lhttp.qingting.fm/live/333/64k.mp3
- 北京城市广播 FM94.5 | https://lhttp.qingting.fm/live/5022463/64k.mp3
- 北京体育广播 FM102.5 | https://lhttp.qingting.fm/live/335/64k.mp3
- 北京Hit FM 88.7 | https://lhttp.qingting.fm/live/15318703/64k.mp3
### 呼和浩特

- 内蒙古音乐广播 FM93.6 | https://lhttp-hw.qtfm.cn/live/1886/64k.mp3
### 西安

- 陕西新闻广播 FM106.6 | https://lhttp-hw.qtfm.cn/live/1600/64k.mp3
### 江门

- 台山人民广播电台 FM90.4 | https://lhttp.qingting.fm/live/5022062/64k.mp3
- 开平广播电台 FM95.6 | https://lhttp.qingting.fm/live/5037/64k.mp3
- 恩平电台 FM97.7 | https://lhttp.qingting.fm/live/20701/64k.mp3
- 新会人民广播电台 FM98.3 | https://lhttp.qingting.fm/live/5061/64k.mp3
- 鹤山电台 FM104.7 | https://lhttp.qingting.fm/live/1286/64k.mp3
### 苏州

- 常熟广播 FM1008 | https://lhttp.qingting.fm/live/2792/64k.mp3
### 延边

- 阿里郎广播 FM91.4 | https://lhttp.qingting.fm/live/5022144/64k.mp3
### 益阳

- 益阳综合新闻广播 FM99.7 | https://lhttp.qingting.fm/live/20314/64k.mp3
### 上海

- 上海东方广播古典音乐 FM94.7 | https://lhttp.qingting.fm/live/267/64k.mp3
- 上海Hit FM 87.9 | https://lhttp.qingting.fm/live/5022038/64k.mp3
- 上海东方广播爱情广播 FM103.7 | https://lhttp.qingting.fm/live/273/64k.mp3
- 上海东方广播新闻频道 FM90.9 | https://lhttp.qingting.fm/live/275/64k.mp3
- 上海东方广播江南都市广播 FM97.7 | https://lhttp.qingting.fm/live/276/64k.mp3
- 上海交通广播 FM105.7 | https://lhttp.qingting.fm/live/266/64k.mp3
- 上海浦江之声 AM1422 | https://lhttp.qingting.fm/live/5021924/64k.mp3
- 上海广播电台新闻频道 FM93.4 | https://lhttp.qingting.fm/live/270/64k.mp3
- 上海广播电台戏剧曲艺频道 FM97.2 | https://lhttp.qingting.fm/live/269/64k.mp3
- 上海广播电台 FM101.7 | https://lhttp.qingting.fm/live/274/64k.mp3
### 潮州

- 潮州交通音乐广播 FM91.4 | https://lhttp.qingting.fm/live/4594/64k.mp3
- 潮州综合频率 FM93.9 | https://lhttp.qingting.fm/live/4596/64k.mp3
### 烟台

- 烟台经典音乐广播 FM94.8 | https://lhttp-hw.qtfm.cn/live/20500097/64k.mp3
- 烟台音乐广播 FM105.9 | https://lhttp.qingting.fm/live/1683/64k.mp3
### 成都

- 成都广播电视台休闲文化广播 | https://lhttp.qingting.fm/live/4892/64k.mp3
- 成都广播电视台交通频道 | https://lhttp.qingting.fm/live/4891/64k.mp3
- 成都广播电视台故事广播 | https://lhttp.qingting.fm/live/5022004/64k.mp3
- 心动电台 | https://lhttp.qingting.fm/live/20500161/64k.mp3
- 四川广播电视台岷江音乐广播 | https://lhttp.qingting.fm/live/1110/64k.mp3
- 四川广播电视台少数民族语言广播 | https://lhttp.qingting.fm/live/1115/64k.mp3
- 四川广播电视台城市之声 | https://lhttp.qingting.fm/live/1111/64k.mp3
### 重庆

- 重庆广播电视台城市广播 | https://lhttp.qingting.fm/live/1502/64k.mp3
- 重庆广播电视台新闻广播 | https://lhttp.qingting.fm/live/1498/64k.mp3
- 重庆广播电视台交通广播 | https://lhttp.qingting.fm/live/1500/64k.mp3
- 大足广播电视台 | https://lhttp.qingting.fm/live/20211676/64k.mp3
- 梁平广播电视台 | https://lhttp.qingting.fm/live/20211646/64k.mp3
### 广州

- 从化流溪河之声 FM95.4 | https://lhttp.qingting.fm/live/15318698/64k.mp3
- 增城电台 FM89.0 | https://lhttp.qingting.fm/live/20211702/64k.mp3
- 广东南方生活广播 FM93.6 | https://lhttp.qingting.fm/live/468/64k.mp3
- 广东城市之声 FM103.6 | https://lhttp.qingting.fm/live/469/64k.mp3
- 广东广播电视台股市广播 FM95.3 | https://lhttp.qingting.fm/live/4847/64k.mp3
- 广东新闻广播 FM91.4 | https://lhttp.qingting.fm/live/1254/64k.mp3
- 广东珠江经济电台 FM97.4 | https://lhttp.qingting.fm/live/1259/64k.mp3
- 广东音乐之声 FM99.3 | https://lhttp.qingting.fm/live/1260/64k.mp3
- 广州交通广播 FM106.1 | https://lhttp.qingting.fm/live/4955/64k.mp3
- 广州新闻资讯广播 FM96.2 | https://lhttp.qingting.fm/live/4848/64k.mp3
- 广州汽车音乐电台 FM102.7 | https://lhttp.qingting.fm/live/20192/64k.mp3
- 番禺电台畅快1017 FM101.7 | https://lhttp.qingting.fm/live/20212427/64k.mp3
- 羊城交通台 FM105.2 | https://lhttp.qingting.fm/live/1262/64k.mp3
- 花都广播电台 FM100.5 | https://lhttp.qingting.fm/live/1263/64k.mp3
### 郑州

- 星光网络怀旧经典广播 | https://lhttp.qingting.fm/live/1222/64k.mp3
- 郑州经济广播 FM93.1 | https://lhttp.qingting.fm/live/1221/64k.mp3
- 郑州音乐广播 FM94.4 | https://lhttp.qingting.fm/live/4921/64k.mp3
- 郑州新闻广播 FM98.8 | https://lhttp.qingting.fm/live/1220/64k.mp3
- 郑州交通广播 FM91.2 | https://lhttp.qingting.fm/live/1211/64k.mp3
### 济南

- 济南音乐广播 FM88.7 | https://lhttp.qingting.fm/live/1671/64k.mp3
- 济南交通广播 FM103.1 | https://lhttp-hw.qtfm.cn/live/1669/64k.mp3
- 历城音乐广播 FM92.8 | https://lhttp-hw.qtfm.cn/live/20500194/64k.mp3
- 山东经典音乐广播 FM105 | https://lhttp.qingting.fm/live/20240/64k.mp3
- 山东音乐广播 FM99.1 | https://lhttp-hw.qtfm.cn/live/1665/64k.mp3
### 惠州

- 惠州音乐广播 FM90.7 | https://lhttp.qingting.fm/live/5021523/64k.mp3
### 全国

- 天主教华语广播 Radio Maria | https://onair7.xdevel.com/proxy/xautocloud_nwct_1310?mp=/;stream/
- 香港电台普通话频道 RTHK | http://stm.rthk.hk/radiopth

## 香港

### 香港

- 商业一台 Metro Plus 1044 AM | http://162.220.162.10:8011/stream
- 迪士尼亚洲广播 FM 100.7 | https://listen.radioking.com/radio/453221/stream/508076

## 澳门

### 澳门

- Hit FM 澳门 91.5 | http://lhttp.qingting.fm/live/15318703/64k.mp3
- 莲花卫视调频台 Lotus FM 97.4 | https://lhttp.qtfm.cn/live/20533/64k.mp3
- 莲花卫视中波台 Lotus 1062 AM | https://lhttp.qtfm.cn/live/20133/64k.mp3
- M80 怀旧电台 89.9 FM | https://stream-icy.bauermedia.pt/m8080.aac
- 强电台 Radio Top 80 89.9 FM | http://live.top80.fm:8086/;
- 亚洲之声 Radio Veritas Asia 1044 AM | http://icecast.eradioportal.com:8000/radyo-veritas-846
- 澳广视葡语台 RTP Macau 97.1 FM | https://radiocast.rtp.pt/antena1madeira80a.mp3

## 台湾

### 台湾

- 古典音乐台 FM 97.7 | http://59.120.88.155:8000/live.mp3
- 警察广播电台 全国治安交通网 | http://stream.pbs.gov.tw:1935/live/mp3:PBS/playlist.m3u8
- 台湾国际广播电台 RTI | https://streamak0138.akamaized.net/live0138lh-mbm9/_definst_/rti3/playlist.m3u8
- 台北国际社区广播电台 ICRT | https://stream.rcs.revma.com/nkdfurztxp3vv
- 警察广播电台 全国治安交通网 FM 104.9 | https://stream.pbs.gov.tw/live/PBS/playlist.m3u8
- 警察广播电台 台北分台 FM 94.3 | https://stream.pbs.gov.tw/live/TPS/playlist.m3u8
- 警察广播电台 宜兰分台 FM 101.3 | https://stream.pbs.gov.tw/live/ELS/playlist.m3u8
- 警察广播电台 新竹分台 AM 1512 | https://stream.pbs.gov.tw/live/SCS/playlist.m3u8
- 警察广播电台 台中分台 FM 94.5 | https://stream.pbs.gov.tw/live/TCS/playlist.m3u8
- 警察广播电台 台南分台 AM 1314 | https://stream.pbs.gov.tw/live/TNS/playlist.m3u8
- 警察广播电台 台东分台 FM 94.3 | https://stream.pbs.gov.tw/live/TTS/playlist.m3u8
- 警察广播电台 花莲分台 FM 94.3 | https://stream.pbs.gov.tw/live/HLS/playlist.m3u8
- 警察广播电台 高雄分台 FM 93.1 | https://stream.pbs.gov.tw/live/KSS/playlist.m3u8

## 马来西亚

### 马来西亚

- 城市广播 CITYPlus FM | https://stream.rcs.revma.com/9ykdmcawe1bwv
- 八度空间电台 Eight无限 FM | https://stream.rcs.revma.com/qp0xrd9mtd3vv

## 新加坡

### 新加坡

- YES 933 新加坡华语流行台 | https://22893.live.streamtheworld.com/YES933_SC?dist=radiosingapore

## 加拿大

### 加拿大

- CHAH 580 埃德蒙顿华语广播 | https://ais-sa1.streamon.fm/7681_64k.mp3
- CHKT 1430 星光中文电台 多伦多 | https://5b2959fe11444.streamlock.net/radio/am1430.stream/playlist.m3u8

<!-- 已从 radio_index.html 导入 157 条唯一电台地址。 -->
