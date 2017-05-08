# Baseball_Data_Analysis
## 参考网站：
1. [轻松看懂棒球统计数据-打击数据篇](http://terryex.pixnet.net/blog/post/36215363)
2. [棒球统计-维基百科](https://zh.wikipedia.org/wiki/%E6%A3%92%E7%90%83%E7%B5%B1%E8%A8%88)
3. [《点球成金》豆瓣电影](https://movie.douban.com/subject/3023164/)
4. [浅谈如何判别打击三围](https://www.sportsv.net/articles/13549)
5. [打击三围-台湾棒球维基馆](http://twbsball.dils.tku.edu.tw/wiki/index.php/%E6%89%93%E6%93%8A%E4%B8%89%E5%9C%8D)
6. [如何计算长打率](http://www.wikihow.com/Calculate-Slugging-Percentage)
7. [纯长打率-维基百科](https://zh.wikipedia.org/wiki/%E7%B4%94%E9%95%B7%E6%89%93%E7%8E%87)

## 数据项介绍
#### `beating_df`
* playerID  —— 球员ID
* yearID —— 当年年份
* stint —— 球员在同一赛季的服役顺序
* G —— 比赛场数（Games）
* AB —— 打数（At Bats）打者完成一次打击，且这次打击并非是成功的牺牲触击、保送、高飞牺牲打的次数
* R —— 得分（Runs）合法及安全回到本垒的次数
* H —— 安打（Hits）在没有失误的情况下，打者把投手投出来的球，击出到界内，使打者本身能至少安全上到一垒
* 2B —— 二垒（Doubles）能使打者在没有守备失误的情况下，安全到达二垒的打击
* 3B —— 三垒（Triples）能使打者在没有守备失误的情况下，安全到达三垒的打击
* HR —— 本垒打（Homeruns）在没有失误的情况下，跑者一次跑完四个垒包

#### `players_df`
* playerID —— 球员ID
* birthYear —— 出生年
* birthMonth —— 出生月
* birthDay —— 出生日
* weight —— 体重（单位：磅 pound）
* height —— 身高（单位：英寸 inch）
* debut —— 在大联盟的首次出场日期
* finalGame —— 在大联盟的最后一场比赛日期（如果仍在活跃则为空）

#### `awards_players_df`
* playerID —— 球员ID
* awardID —— 奖项ID
* yearID —— 年份
