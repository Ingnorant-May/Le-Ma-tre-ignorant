# AER, 中国大运河上的叛乱: 262年间的证据, 运用DID, CIC, SCM等方法...
![](https://r.sinaimg.cn/large/article/ae8ef5a845869dc6802c15896f5d5106)

凡是搞计量经济的，都关注这个号了  

**邮****箱：** **econometrics666[@126](https://weibo.com/n/126).com**

************所有计量经济圈方法论************************丛的code************************文件,************微观数据库和各种软************************件都放在社群里.欢迎到计量经济圈社群交流访问************************.************

![](https://r.sinaimg.cn/large/article/e3b48da1ee9dab9dad511edb9934ac06)

前些日，我们分享了“ [首篇中国量化史文章被AER接受了！用了DID, CIC, SCM等因果推断方法！](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448091408%26idx%3D1%26sn%3D56b4a8e4361de2a977be2d4e4a87dad8%26chksm%3Db323343e8454bd280848e2c340d5b7b52e32f3c100846aa1fa06132a04ef889b323353b763a4%26scene%3D21%23wechat_redirect) ”，今天，就这篇AER文章做出具体的解读，做政策评估的学者可以关注其中的方法。

**_正文_**

关于下方文字内容，作者：周宁哲, 武汉大学经济与管理学院，通信邮箱： inze\_zhou[@foxmail](https://weibo.com/n/foxmail).com

作者之前的文章：1.[Top金融,经济与会计期刊中的文本分析, 一项长达2万字的综述性调查](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448092177%26idx%3D1%26sn%3D83d0467f5b168d47b53ebd2198ca82c7%26chksm%3Db323313f8454b82938fc7ef78062fd127e6a2b6551f4c81988cc227a2877089ede018128f1df%26scene%3D21%23wechat_redirect)，2.[前沿: 解决内生性问题的无工具变量推断法](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448090575%26idx%3D1%26sn%3Da79620951d64a7884efafc724f01eb4d%26chksm%3Db32338e18454b1f75604e75b03c6bd3293e80cb2616ad002993464aadc344d8425a55886303e%26scene%3D21%23wechat_redirect)，3.[断点回归设计RDD的原理和实证指南, 年龄, 地理, 分数等断点应有尽有](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448094388%26idx%3D1%26sn%3D1fe1f2cccaafc3ed418632d8eae51f1f%26chksm%3Db323299a8454a08c76ce5ccb0e7145dc70b4c9e2b9f0e8d25037dff0a07ca192a33f4b8c5771%26scene%3D21%23wechat_redirect)

> Yiming Cao, Shuo Chen, 2022, Rebel on the Canal: Disrupted Trade Access and Social Conflict in China, 1650–1911, American Economic Review.
> 
> This paper examines the effects of the closure of China’s Grand Canal - the world’s largest and oldest artifificial waterway - which served as a permanent shock to regionat trade access. Using an original dataset covering 575 counties over 262 years, we show that the canal’s closure led to social turmoil that engulfed North China in the nineteenth century. Counties along the canal experienced an additional 126% increase in rebelliousness after the canal’s closure relative to their non-canal counterparts. We explore several prominent mechanisms that potentially explain our results and find the most support for disrupted trade access, especially in urban areas. Our findings thus highlight the important role that continued access to trade routes plays in reducing conflict - a classic conjecture that has rarely been directly tested in a causal context.

目录

![](https://r.sinaimg.cn/large/article/995a4f5cc7cb9c7957a7a95b08ac015e)

一、 引言  

--------

关于贸易机会之于社会稳定的作用已有广泛讨论。一方面，贸易机会增加居民收入、提供就业机会，维持社会稳定；另一方面，通达的贸易环境也为动荡的出现提供沃土。文章以1826年在大运河施行的“漕粮海运”政策为准自然实验，试图探讨贸易机会与社会稳定间的因果联系。

中国的大运河是世界上最大、最古老的人工水道，800余年间持续为内陆航运与商业保驾护航。随着1826年清廷所定“漕粮海运”政策逐步落实，大运河逐渐废弃（1855年后失去维护；1901年正式弃用），周遭城市被动失去原有贸易通道，其后不久，动荡四起。

文章使用涵盖大运河流域周边六省共计575座县域、262年间的清廷官方统计数据，该数据详细记载了地方叛乱的时空信息；利用双重差分模型，将1826年视为外生冲击发生年，比较“运河县”（运河流经或穿过的县域）与其他县（距运河较远县域）间地方叛乱发生数量的差别。研究表明，与偏远县相比，冲击产生后的运河县每百万人口叛乱人数比增加了0.0414人。进一步，文章发现，政策冲击对叛乱的效用与县域内运河长度（地理依赖）、距运河10km内集市占该县集市份额（经济依赖）有关；且影响效果随距运河距离增加而衰减。多种稳健性检验方式证实了结果可信。机制上，研究发现运河废弃可能通过“贸易机会的丧失”影响着叛乱起义的发生，这与现有历史研究相符合。

文章贡献大致有四：①基于来自中国的准自然实验证据发现贸易可达性丧失会显著增加社会冲突发生概率，推动“贸易可达与社会稳定”这一重要议题的发展；也展现出封闭经济体中贸易波动对社会稳定的潜在负面影响。②研究重点关注永久冲击、国内贸易以及城市地区的发展问题，丰富现有文献；同时利用子样本取样法剔除掉贸易冲击中收入冲击的作用。③研究扩展了关于交通基础设施的相关文献，且基于一种与现有大多研究所关注的当代交通体系不同的历史视角。④文章从实证经济学的角度加深了对19 世纪以来中国华北地区社会经济动荡现象的理解，在更为长期、宏观的视角下进行了讨论。

二、 背景信息
-------

#### （一） 关于大运河

![](https://r.sinaimg.cn/large/article/3633b37e31ee4b63c44c12608ed6c1b4)

![](https://r.sinaimg.cn/large/article/0b36d96ee838673bba2378c993dacb2c)

长达1776公里的大运河是世界上最长、最古老的人工水道，其位于中国东北和中东部平原，北接北京、南连杭州。1820年，有超过1.26亿人口居住在运河周遭六省，占当时世界总人口的15%左右。

大运河建立的一个重要目的是保证北京的粮食供应，中国政府使用“贡粮(tribute grain)”制度，通过大运河将南方生产的谷物运往北方。因此，政府会主动维护运河的通畅。

同时，大运河推动贸易发展、提供就业机会，客观上使邻近地区受益。例如，临清，在修建大运河前只是一个小县城，到清朝初年，它已发展成为颇具规模的区域性贸易中心，并于1777年升为自治市(municipality)。人口密度也是经济繁荣的一项证明，在1820年，“运河县”的人口密度比非运河县高出45%。

#### （二） 大运河的废弃

清朝后半叶，政府放弃了大运河。1825年，接连发生的暴风和洪水使大运河与黄河交界处严重问题，从1826年开始，清廷决定用沿中国东海的新航线替代传统运粮路线。值得注意，没有足够证据表明，对大运河的这次重大变革出于对运河流域曾有的或预期可能会发生的起义叛乱的考量。

大运河的废弃（与新航道的发展）是逐步发生的，1826年开始在江苏省进行“试点”；1852年扩大到江苏和浙江两省；1855年后，停止对大运河的运定期维护（政府已几乎完全通过海运运输贡粮）；到19世纪末，大运河许多河段已堵塞至无法通航；1901年清政府正式宣布关闭大运河。

废弃大运河使运河周边城市丧失了这条既定贸易路线带来的利得。陆路高昂的运输成本导致区域间贸易急剧减少、依托运河的工人大量失业。如上文所提的临清，其人口从18世纪末的20多万下降到20世纪初的不到5万。

有趣的是，来自不同领域的声音都暗示着大运河的废弃与该地区随后的社会动荡有所关联。比如，历史学研究发现运河废弃过程中失业的工人与叛乱团体形成关系密切；又如地方民谣中感叹运河废弃严重后果的唱段。

基于此，文章以相对系统的方式对这一“假设”展开评估。

三、 数据
-----

文章从历史资料中整理出时间跨度为1650至1911年、涵盖大运河所流经（或临近）的六座省下575个县的面板数据集。

在县一级进行实证分析优势在于：①县域间的行政边界相对稳定；②为评估更高层次（省、市）可能存在异质性提供基础。

#### （一） 因变量：叛乱

文章主要的因变量是各县域各年度的叛乱数量（以该县初始人口进行标准化）。首先，利用《清实录》中信息计算每个县每年的叛乱数量（关注叛乱的产生，不包括现有叛乱的跨年度延续），在样本期间，总共有1114次叛乱纳入讨论。随后，结合Cao (2001)及Liang(1980)的县域人口研究对叛乱数量标准化。

#### （二） 处理变量

文章采用四种方法构造处理效应：

基准分析：利用县域边界和大运河路径的空间交叠，将与大运河接壤或包含部分河段的县域纳入处理组，远离运河的县被纳入控制组。样本中575个县域有73个被划分到处理组（称为“运河县”）。

扩展分析：①地理依赖度：使用该县所包含的运河部分的长度代理；②经济依赖度：由距离运河10公里以内的镇（指起到地方集贸作用的小型单位）在该县所占份额代理；③空间梯度：计算样本中县域的行政中心到运河的距离，减少运河影响受到的县界约束。

#### （三） 控制变量

地理特征：①各县域土地面积；②各县域地形崎岖度指数，主要参考Nunn & Puga (2012)、Riley et al. (1999)等。

人口特征：①控制1600年各县域人口密度，参考Cao (2001) 及Liang (1980)。

气候特征：①温度异常，参考Mann et al. (2009)的统计资料，异常大致每三年发生一次；②极端气候，参考Chen& Kung(2016)统计资料，极端气候出现平均周期远长于异常气候。

农业特征：①传统作物：湿地水稻和小麦的适宜性指数；②新世界作物：玉米和甘薯的种植周期。

各变量描述性统计结果如下：

![](https://r.sinaimg.cn/large/article/a49bc8cd1d9f2766c6b886fd1fb7c62e)

#### （四） 特征性事实

正式实证分析前，文章提供了一些描述性证据。

下图展示运河叛乱的时间分布。可见，在运河废弃后，叛乱的频率明显增加：从1825年前的每年1.37次增加到之后的每年10.47次。这个数字在1861年达到峰值，并直到1870年代也没有下降。

![](https://r.sinaimg.cn/large/article/452c3e03c48b882069736c920d484d90)

下图中左右两侧分别展示运河废弃前后叛乱的空间分布。可见，在运河放弃之前，叛乱的频率较低，但分布较广；废弃后叛乱的总数增加，且分布更为集中。值得注意的是，临近运河的区域，在冲击发生前后的相对变化更大。  

来自时间及空间分布的证据表明，运河的废弃可能促成了叛乱的全面增加。对运河废弃前后的各县叛乱数量简单进行t检验，其结果也支持上述推断。

![](https://r.sinaimg.cn/large/article/706809390f0a375da070ed96fcb0a21b)

四、 实证策略及结果
----------

#### （一） 实证策略

文章首先采用标准DID模型进行分析：

![](https://r.sinaimg.cn/large/article/47ed1f4c11b5f49f4a89c4e937267942)

方程中下标c指县，t指年。Yct 指c县在t年记录的叛乱数量，按期初的人口规模归一化，分析中对该值进行反双曲正弦变换(arcsinh)，以处理叛乱数量中的潜在极端值。AlongCanal为虚拟变量，用于区分“运河县”与“非运河县”；Post同样为虚拟变量，将运河废弃后的年份记作1。方程中还包含对县和年的固定效应及一系列控制变量。

同时，考虑到大运河的废弃是在几十年间渐进实现的，文章对每十年间运河带来的影响加以刻画，如下图：

![](https://r.sinaimg.cn/large/article/93c8658d0449ea9ba6cbe5662001b398)

结果表明改革在1826年后即刻开始生效，随着改革的推进，其影响有所增加，至1860s开始降低。这也佐证了文章以1826年作为冲击发生年的合理性。

此外，文章还进行了对冲击发生年前后运河县与非运河县间差异趋势的检验，结果表明其间差异是微小且不显著的。

#### （二） 基准分析

基准分析结果如下表：

![](https://r.sinaimg.cn/large/article/4d958f2da8884966ebc9914a6fd9d8fa)

表中后3列在第一列基础上逐步加入不同固定效应：冲击前的人均叛乱数量与年份交乘（使冲击影响更好地作用于在首期更易产生叛乱的县域）、省份与年份交乘和市（州）的时间趋势。关注系数报告聚类到县域的标准误和康利标准误(Conley standard errors)。各列结果均呈现出正向显著影响，如第1列系数表明冲击发生后每百万人口中叛乱增加0.0414，相比与样本均值(0.0328)，增幅达126%。

文章同样考虑运河县与非运河县间可能存在的系统性差异，包括地理、气候、人口和农业，将其与表示冲击发生的虚拟变量Post交乘纳入控制，结果与此前相近。

稳健性检验中，文章考虑有关样本选择、结果测量和标准误调整这几项模型设定，证明其不影响结果稳健性。

#### （三） 处理强度讨论

基准分析中假定冲击影响受县域边界所限，这一假定或显武断。本节对此进行宽松。

###### 1\. 运河县内的处理强度

文章使用两种指标度量一座运河县对大运河的可能依赖程度。

其一为地理依赖，使用大运河在该县境内的长度（以该县面积标准化）度量；其二为经济依赖，使用距运河10公里范围内的（作为集市的）城镇占该县城镇的份额代理。

![](https://r.sinaimg.cn/large/article/f4b43c21b188c8e7951300a970bbcba6)

上两式分别度测了两指标平均和分组的处理效应，结果分别见以下表、图：

![](https://r.sinaimg.cn/large/article/1d91dbe8de7216ced54672644d4d3253)

![](https://r.sinaimg.cn/large/article/88b6472341ff8167761211c954f8e0a0)

不难看见，冲击带来的影响随着县域对运河的依赖程度（地理上和经济上）的增加而增加（尽管在地理依赖上不是严格单调的）。

###### 2\. 对非运河县的溢出

冲击带来的影响也可能共通过贸易往来等方式辐射到非运河县。文章使用总样本中各县域地理中心距大运河的距离与表示冲击发生时间的虚拟变量交乘，对冲击的溢出效应进行测度：

![](https://r.sinaimg.cn/large/article/7d5c9851910ca889a3fcf84eaf86a54d)

以上方程构建思路与上一小节相同，其中分组估计时以25km为间隔对Distance分组。结果如下：

![](https://r.sinaimg.cn/large/article/f17ff8ff57ea212d3d412deabafef970)

![](https://r.sinaimg.cn/large/article/eaabf1e28d87bbc6cac190699e34b9ce)

可见，正如所预期，冲击带来的影响随距离运河距离的增加而减少，而这一空间范围大致能达150公里。  

五、 进一步检验
--------

由于十九世纪中后期的中国正处于一段异常动荡的时期，来自社会环境中可观测、不可观测的事件可能对前文研究结果形成干扰。为进一步证明研究结论的稳健、可信，文章从以下三种角度展开说明：

#### （一） 变更估计方法

###### 1\. 双重变换法

DID模型中部分前提假设较为严苛，尽管前文实证分析中以对其作出检验，但为避免模型上的可能存在的偏误，文章首先使用双重变换法(Changes in Changes, CIC)进行检验。

CIC估计并不比较处理组和控制组的平均结果，而是试图估计反事实结果的分布，通过与实际分布进行比较，非参数化地估计处理效果。依照 Athey & Imbens(2006)和Melly & Santangelo(2015)的经验，分两步进行CIC估计，所得结果与基准回归相合，如下示：

![](https://r.sinaimg.cn/large/article/16f4e0041002ebaababbc25d7d9fafff)

###### 2\. 合成控制法

第二种估计法为合成控制法(Synthetic Control Method, SCM)，SCM法采用一种数据驱动的方式实现控制组中样本信息的加权组合，以期接近冲击发生前处理组被解释变量的演进趋势，进而以估计结果作为真实演进结果的反事实。

根据Cavallo et al.(2013)，badie(2021)和Galiani & Quistorff(2017)的经验，文章进行SCM估计，结果如下图。注意，十九世纪中期叛乱的激增与当时社会矛盾激烈的现实相符，运河县与非运河县都经受了这一整体环境层面的影响。

![](https://r.sinaimg.cn/large/article/4ccb3fe56134e093d385ad410e6e2ad3)

#### （二） 安慰剂检验

由于大运河在历史中长时期存在，运河县可能在很多属性上与非运河县不同。尽管基准回归中已控制大量协变量，但其他未知或不可观察的差异仍可能令人怀疑估计结果。在本节中，文章设计以下两种方式进行安慰剂检验。

###### 1\. 运河废弃的南北差异

运河失去维护后，其北部河段（黄河以北）更先淤塞失效，南部河段则在一段时期内保有一定粮食运输、商品贸易等功能。文章设置三重交乘项 以捕获南北差异，同时加入 捕获南北间县域差异。实证结果如下表，显然运河废弃带来的影响存在显著南北差异，即运河废弃这一冲击对叛乱的影响并非受其曾经存在的干预（北部地区曾有运河，但该地域河段失效后，叛乱相对南部显著多）。

![](https://r.sinaimg.cn/large/article/65eca96daa3d668251cc054a4cafcc12)

###### 2\. 替代线路  

此外，文章选用与运河功能近似的长江、黄河、沿岸航线和驿路替代大运河进行检验，结果对前述结论实现进一步佐证。

![](https://r.sinaimg.cn/large/article/100f61bb992fc234e4b4519d091e89f5)

#### （三） 重大历史事件

文章详细讨论了改革过程中发生的两个重大事件：第一次鸦片战争（1840-1842）和太平天国运动（1851-1864）会如何影响对运河废弃的估计。

值得注意，这两个事件的发端均在（文章讨论的）运河流域之外，但其后移动至运河流域内。中英第一次鸦片战争于1840年在广东省开始，直到1842年7月，英军攻占宁波、上海和镇江，随后其舰队切断大运河；太平天国运动于1851年在广西省开始，沿长江进入安徽、江苏和浙江等省。1853年于南京“建国”后，太平军北进山东和直隶未果，但在此期间，由于大平军的干扰，粮食朝贡系统近乎瘫痪。这些事件可能从几个方面干扰估计结果：

###### 1\. 叛乱仅统计由鸦片战争和太平天国所致者

这一质疑不可能成立。首先，文中分析仅限于已知在当地爆发的叛乱，而排除了现有大型叛乱团体的行动。其次，尽管英军和太平军都试图控制运河运输的发源地（尤指南京、杭州），但他们都未将战事沿运河推进很远，特别是运河北部受影响较小。第三，文章检验表明，将样本期限制在太平天国发端前50年窗口结果依然稳健，检验结果如下：

![](https://r.sinaimg.cn/large/article/846d4c6853cce2b90741799fcb9311cd)

###### 2\. 鸦片战争和太平天国导致叛乱统计不精确

对这一问题，文章在排除受这些事件直接影响的县的情况下重新进行分析。结果见下表（前4列）。显然，结论几乎没有变化。

![](https://r.sinaimg.cn/large/article/d752660d3785d3275d3274c54f77d425)

###### 3\. 鸦片战争和太平天国与运河废弃相互作用促进叛乱产生

这一问题可能有两个渠道：1）鸦片战争和太平天国运动可能鼓动当地居民反抗清政府（互补）；2）这些运动可能从地方招募新军，从而减少了当地地方性叛乱的发生（替代）。

对此，文章测度了被占领地区在运河废弃与两事件中的三重交互效应，见上表后4列。结果表明，鸦片战争影响不大。而太平天国运动对直接受影响的地区有明显的负效应。这可能是因为一些有造反倾向的人在太平军抵达他们所在地区后加入了该团体（因而没有自己造反）。当然，重要的是，没有发现证据表明运河县对这些大事件的反应比非运河县更激烈。

六、 机制讨论
-------

本节讨论了运河关闭阻碍政治稳定的两种潜在机制：国家镇压能力的降低和贸易机会的丧失。使用多种方法来评估后，发现贸易损失作为影响机制的证据更为充分。此外，文章还进一步研究了贸易损失所引起的收入冲击及其长期影响。

#### （一） 国家镇压能力

由于县域一级上国家镇压能力估计的困难，文章采用两种间接方式测度。

###### 1\. 政治重要性

文章采用两种衡量政治重要性的方法。第一个衡量标准考虑18世纪50年代分配的军事机构规模，显然，这直接代理了对地方的镇压能力以及政府对该县军事重要性的认识；第二个衡量标准是一个县是否是市一级的行政中心。结果见下表前两列。

可见，（交乘项）系数不显著异于0。因此，没有证据表明，来自运河废弃的冲击对政府更重视的地区带来了更多（或更少）的叛乱。

![](https://r.sinaimg.cn/large/article/4f399f4b98242ee439b72d7fc08b5e94)

###### 2\. 叛军轨迹

文章在《清史稿》中提取了相关地方叛军进攻或撤退到县域的记录，叛军的战略决策应能反应国家在地方层面控制力的变化。如果运河废弃降低了运河沿线的镇压能力，那么叛军会更易于选择运河周边县域作为进攻目标或退路。结果如上表后两列。

与预期不同，运河县在冲击后受到攻击的频率反而略有减少；而将运河县视为退路的叛军数量在冲击前后并无显著变化。

#### （二） 贸易机会

运河废弃在客观上关闭了直接进入这一既定贸易路线的通道。在前文分析中，其实已有证据表明这一因素是一种可能的影响机制（如影响与集市份额有关、北部比南部受影响更甚等）本小节中考虑三种证据支持这一机制。

###### 1\. 集市数量

文章将1820年和1911年每个县的集镇数量纳入回归模型，结果如下表第一列，显然，运河的关闭极大地阻碍了19世纪运河沿岸集镇的发展，这直接证实了冲击对区域贸易的破坏性影响。

###### 2\. 替代贸易路线

文章重点考虑华北地区的一条替代性南北陆路交通路线，将其与主要解释变量交乘。结果见下表第一列。发现如果一个运河县能够使用替代路线，那么叛乱的数量会显著减少(5%)。

###### 3\. 气候冲击

最后，文章将运河的废弃与表示温度异常的年份的虚拟变量交互，结果在下表第三列。结果表明运河对天气引起的社会冲突有缓解作用，而运河废弃后缓解效应则不再存在。这条证据虽然不太直接，但也暗示着运河废弃可能通过扰乱运河曾经维系的贸易通道的环境而促成叛乱。

![](https://r.sinaimg.cn/large/article/abfe193d9a3ffdf180171e137ed8d526)

#### （三） 进一步讨论

在本小节中进一步讨论贸易损失所引起的不同类型的收入冲击。第一，贸易机会的丧失可能增加农产品的交易成本，导致消费者和生产者的福利损失；第二，运河废弃可能会打击从事贸易相关工作的港口城市工人，如水手、码头工人、商人等。

###### 1\. 农业成本

首先，文章研究谷物价格对运河废弃的反应。如果运河关闭增加了农产品的交易成本，那么预期粮食价格将会上升。回归结果表现出正系数，但并不显著。

随后文章研究运河废弃的影响是否在不同地区存在差异。如果农产品交易与叛乱刺激有关，有理由预期，在更适合农业的地区，叛乱的影响会更大。结果表明叛乱的产生在不同的作物适宜性水平（作为地区农业适宜性的代理）上没有异质性的影响。实证结果见下表：

![](https://r.sinaimg.cn/large/article/dbb79368c851dfec585bbdc652a58f53)

###### 2\. 工人失业

由于港口城市工人的收入损失（或失业）与当地整体贸易环境关联紧密，为提取出港口工人所受影响，文章选用大运河和长江交汇处的地区作为子样本，在这个样本中，运河的消失带来了巨大的贸易冲击，而对港口工人的收入影响却很小。

![](https://r.sinaimg.cn/large/article/92799c306cdbd4f53ff9f35dbae40cb8)

上图展示离长江100、200、300和400公里的子样本的估计系数。可见，点估计值随着距长江距离的增加而增加，但不显著。尽管如此，这一研究结果与历史学叙述是一致的，即运河流域的水手和码头工人组织在运河废弃后不久就发展成为黑帮形式的结社。

历史学家描述了运河关闭与有组织帮派的出现和几十年来的暴力事件之间的潜在联系，包括青帮（二十世纪初期中国最大、最强大的有组织犯罪集团之一）的出现、共产主义革命的兴起、以及文化大革命期间武装冲突的盛行。文章也通过实证回归对其进行了简单的检验，证实其论断。

因此，实证结果虽不具有统计意义上的因果关系，但至少表明港口劳工向黑帮的转变具有较为深远的影响。

七、 结语
-----

文章研究了中国大运河的废弃与随后19世纪华北地区的社会动荡之间的联系。利用一个包含262年间575座县域信息的数据集，文章证明，运河废弃后，运河县比非运河县更频繁地经受叛乱。而这种影响主要是由在地理上、经济上更依赖大运河的县所驱动，且其效应能够扩散到周边约150公里。机制上，最可能的路径是，大运河废弃使得周边地区贸易机会丧失（港口工人失业），进而破坏社会稳定。

文章在统计意义上对持续贸易通达促进和平这一经典观念进行检验，同时对19世纪华北地区的长期社会动荡进行了新的解读。研究认为社会经济机会的丧失是促成帝制中国末期持续、反复的地域叛乱的主导力量之一。

![](https://r.sinaimg.cn/large/article/681f98145f0c4438165709c70b1f1814)

* * *

下面这些短链接文章属于合集，可以收藏起来阅读，不然以后都找不到了。  

****2.5年，计量经济圈近1000篇不重类计量文章，****

**可直接在公众号菜单栏搜索任何计量相关问题****,**

**Econometrics Circle**

**数据系列** **：**  [**空间矩阵**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448060009%26idx%3D1%26sn%3Dd0e09b9da56adc839d0bf2829f74a798%26chksm%3Db323b34784543a51705b584f9678b9d92f6bc4f8ccf3dcca3ef0d0fc08f04aadb97a33bb0d26%26scene%3D21%23wechat_redirect) **|** [**工企****数据**](https://weibo.cn/sinaurl?u=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448059634%26idx%3D1%26sn%3D5312d3cc381834b62c1eb67e9a8a1f6d%26chksm%3Db323b1dc845438cafe045495c652c9817d6e6985b7af9063e4d197ad242cab9e42dfa4e9288f%26scene%3D21%26token%3D15317526%26lang%3Dzh_CN%23wechat_redirect) **|** [**PM2.5**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448058119%26idx%3D1%26sn%3D79d1e1f0e35a367a76eb0576e49bb963%26chksm%3Db323ba298454333fd4599a881dc19cd7fdba35965e9d05bd7a260a92cba3841bc3953e1d0543%26scene%3D21%23wechat_redirect) **|** [**市场化指数**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448059310%26idx%3D1%26sn%3D38f7b997958eb22a33144f9d8a8f6b47%26chksm%3Db323b68084543f966982777e972d698f35d3b9b5de7f314f5ab386839b5933d57c795da6f5c9%26scene%3D21%23wechat_redirect) **|** [**CO2数据**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448058145%26idx%3D1%26sn%3Dfce08fd7873a13f0bab2c08a9f85fa1b%26chksm%3Db323ba0f84543319d1b1c823b7ca718eedf8632ce637dd57a4a77ced784dfde6310583c1de81%26scene%3D21%23wechat_redirect) **|** [**夜间灯光**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448063102%26idx%3D1%26sn%3D33651bd4acc42c6ee1d62056f90c0a8f%26chksm%3Db323a75084542e46c3cdcb7a56da6ff84b2f42727df77863cb2d643f3c3d17d3508ea08ce3e9%26scene%3D21%23wechat_redirect) ****|**** [**官员方言**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448065433%26idx%3D1%26sn%3Da9462690887c158c88a3cac56d2b29fd%26chksm%3Db3235eb78454d7a1a5d116f42eb1a94e068cde86e58acfbe5e9cb120c1ccaf01d2d2b305fcaa%26scene%3D21%23wechat_redirect) ****|**** [**微观数据**](https://weibo.cn/sinaurl?u=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448062811%26idx%3D1%26sn%3D202fc87eb6f342e5dcb8f2158dfc6ceb%26chksm%3Db323a47584542d63fbcb79ab702d51b229d35132a9e91c0f85f1a4fff86aa8841dba21aa45b2%26token%3D1841432546%26lang%3Dzh_CN%26scene%3D21%23wechat_redirect)  **| 内部数据**

**计量系列** **：**  [**匹配方法**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448062566%26idx%3D1%26sn%3Df44f630371c71e3b4c224764a9119544%26chksm%3Db323a54884542c5eaa72494b8d1ad0cc4996b8a334e6ae56c37b3cb2ec4e0ad9d3d785a4cfcb%26scene%3D21%23wechat_redirect) **|** [**内生性**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448062564%26idx%3D1%26sn%3D9c8ec12753691fbb5a8a24a218f98dfd%26chksm%3Db323a54a84542c5c4e2b34cbd7311b68af477618ee8e7318389073ea66a18dc4b2aa509bd798%26scene%3D21%23wechat_redirect) **|** [**工具变量**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448063055%26idx%3D1%26sn%3D41edd00addaafde5455df840a721d57b%26chksm%3Db323a76184542e778798ee766e32ab09ea91262fe2513c3ed8299ed74320156112413c5a6b63%26scene%3D21%23wechat_redirect) **|** [**DID**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448061904%26idx%3D1%26sn%3D2faa0b5c7f589123357936914bc00653%26chksm%3Db323a8fe845421e8406084be49bba42993578da2d931572b830e9c8c72fb66e0a7148dc040ad%26scene%3D21%23wechat_redirect) **|** [**面板数据**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448062552%26idx%3D1%26sn%3Dd06aeea68eb98c108b6788316262d839%26chksm%3Db323a57684542c6028d9810b33bc24fb4092931bfa5dfb2c2f3a4f9dc30371a689d144d4e240%26scene%3D21%23wechat_redirect) **|** [**常用TOOL**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448058131%26idx%3D1%26sn%3D775cff0263536feabfdfae383d22c365%26chksm%3Db323ba3d8454332b2551fda4b21e47ee00b68a2e6aee4a542a26194e07d517034189839f15c1%26scene%3D21%23wechat_redirect) **|** [**中介调节**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448064821%26idx%3D1%26sn%3Df5041659920ee9f0cf1222af629acde8%26chksm%3Db3235c1b8454d50d2adb6e82cb1c6780be2d9bb5a108cc2a7876fd92e9148df97538143ad2f6%26scene%3D21%23wechat_redirect) **|** [**时间序列**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448065022%26idx%3D1%26sn%3D1e33ca30af79f4c1034f12695c33ceab%26chksm%3Db3235cd08454d5c6076fbd6b178da41a24065146d904ad1942a44045e181c00d8dc2ca0a2302%26scene%3D21%23wechat_redirect) **|** [**RDD断点**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448065475%26idx%3D1%26sn%3D2a59d1f706edf1246dfb55b66b9afe77%26chksm%3Db3235eed8454d7fbdcc21ecd6597aa15890cafacf66462c71fe4050601748f54e30805c5778e%26scene%3D21%23wechat_redirect) **|** [**合成控制**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448057440%26idx%3D1%26sn%3D225b8679d4aedc559a83d298e6d652f1%26chksm%3Db323b94e84543058ce552c4265a7d677aa90c8ed249f05145d60135e248a691ea19a617a24a3%26scene%3D21%23wechat_redirect) **|** [**200篇合辑**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448069237%26idx%3D1%26sn%3Dbf640bf9c102ce2ec4510947e712df6a%26chksm%3Db3234f5b8454c64db969ca3b0b810ba7440930c485b68a8d1da0c775bb539d4c2d5f9a828e53%26scene%3D21%23wechat_redirect) **|** [**因果识别**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448071920%26idx%3D1%26sn%3D0d1d77a5ef2cb299ccd8490ba90d661d%26chksm%3Db32341de8454c8c8a37c136ce86e29a891619aed862ef413572573dde7619e12ffa095e287a8%26scene%3D21%23wechat_redirect) **|** [**社会网络**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448068171%26idx%3D2%26sn%3Dfe032014f4077f8b2e3c0922a79ae84b%26chksm%3Db32353658454da73a9a8d25216f2b55729a0e9028a2b76ebcaa627401e710773824ca116dd65%26scene%3D21%23wechat_redirect) **|** [**空间DID**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448071482%26idx%3D1%26sn%3D10065b277b091029305535520da164f0%26chksm%3Db32346148454cf0200ba64bee439af791a9a466d3e34482365abac9b70d0abbfa7350f2e4751%26scene%3D21%23wechat_redirect)

**数据处理** **：**  [**Stata**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448065464%26idx%3D1%26sn%3D5d47e75e0572f76d2435b16859cfa4e0%26chksm%3Db3235e968454d780b73d308367b5cf94a9b153878cf9a6d62c6a050e8f9f57b2622ff0e496bd%26scene%3D21%23wechat_redirect) **|** [**R**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448058238%26idx%3D1%26sn%3D827485961988e6e8564e0cdc74802377%26chksm%3Db323ba508454334626f198761497dbaf946e882c5ce2cf906b48b50a0ef287f704bee52ed45e%26scene%3D21%23wechat_redirect) **|** [**Python**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448061325%26idx%3D1%26sn%3D82452e48f4c8d6128fda45b2ec8b7a4e%26chksm%3Db323aea3845427b507ef729c2b6eb6368eaa49e784638f2a35d6bc3155444766efa5d524b3c1%26scene%3D21%23wechat_redirect) **|** [**缺失值**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448061020%26idx%3D1%26sn%3D1deed45e15bf85519c6c8ee96ff78651%26chksm%3Db323af7284542664845bec10ddee7aca83db4ac1325c98382ad1020bbd65da8419e9de2e3f57%26scene%3D21%23wechat_redirect) **|** [**CHIP/ CHNS/CHARLS/CFPS/CGSS等**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448056970%26idx%3D1%26sn%3D60464a09b72a72da002d33ddc2f98013%26chksm%3Db323bfa4845436b24f87b67bc3a06d46a1da7270e7e7bde6528edc3a5015f69007b923f91a6b%26scene%3D21%23wechat_redirect) **|**

**干货系列** **：**  [**能源环境**](https://weibo.cn/sinaurl?u=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448063896%26idx%3D1%26sn%3D3eb5a7ee2ee8b21f8b4ea6dae4730ecf%26chksm%3Db323a0b6845429a02c0968bfd19baa21d1dcfdc2cd0d3dc49148ceb2d57213ec78b43f4d58c0%26scene%3D21%26token%3D15317526%26lang%3Dzh_CN%23wechat_redirect) **|** [**效率研究**](https://weibo.cn/sinaurl?u=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448063909%26idx%3D1%26sn%3Dec58cdbc619804982ddf200975a5d65f%26chksm%3Db323a08b8454299dc902a12085add4d80e07da6105b4484bf94d05e1bce5ea101d765a53cd0a%26scene%3D21%26token%3D15317526%26lang%3Dzh_CN%23wechat_redirect) **|** [**空间计量**](https://weibo.cn/sinaurl?u=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448058317%26idx%3D1%26sn%3Dbe11b13a539a73d0a15e512f7cb576f7%26chksm%3Db323bae3845433f5bbb0cea353f44febe1acc0f3f3a6397c3a835b702f6577a37030fbccbd79%26scene%3D21%26token%3D15317526%26lang%3Dzh_CN%23wechat_redirect) **|** [**国际经贸**](https://weibo.cn/sinaurl?u=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448062875%26idx%3D1%26sn%3Db3ac56e734e2ec8f7794359274ace54b%26chksm%3Db323a4b584542da315de07363e8205b18d91b38521394e115325523fa51c50d4c3bb88b9dfce%26scene%3D21%26token%3D15317526%26lang%3Dzh_CN%23wechat_redirect) **|** [**计量软件**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448063081%26idx%3D1%26sn%3D3b6c35626a442a2a27b3dc5affb09a10%26chksm%3Db323a74784542e51316dd54f482c4298b76bf33147e91076b842c3fdafefda443997d2d14e3c%26scene%3D21%23wechat_redirect) **|** [**商科研究**](https://weibo.cn/sinaurl?u=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448062538%26idx%3D1%26sn%3D95207383c54fc894387cbe3e3ebe23c9%26chksm%3Db323a56484542c725034c37a7554e60fcbeabfa5a2d9624cb2642e85e13ca4fc8959fdbeab0d%26scene%3D21%26token%3D15317526%26lang%3Dzh_CN%23wechat_redirect) **|** [**机器学习**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448064997%26idx%3D1%26sn%3D023597da1e8f7251eda227fa7db086a5%26chksm%3Db3235ccb8454d5ddc11b2d8acc7e7356119153be4b746b66ed92248179ca7404ecfd6c9bb06c%26scene%3D21%23wechat_redirect) **|** [**SSCI**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448062524%26idx%3D2%26sn%3D528091780d78c3e1a1a2c27151acaa8e%26chksm%3Db323a51284542c0459af59af8adb02dc0ce63da40ea359c088815eecb8065666c4c504f1e7d0%26scene%3D21%23wechat_redirect) **|** [**CSSCI**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448064927%26idx%3D1%26sn%3Db49de8b7f1176e911f70f928a9aa3da4%26chksm%3Db3235cb18454d5a789e54dcdb3f8cffe23870db008dcedf9f58f452d259b8cf273fa20bc2cb1%26scene%3D21%23wechat_redirect) **|** [**SSCI查询**](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448065664%26idx%3D1%26sn%3D7eb9a12382669bdb5eb25f8bf183a609%26chksm%3Db32359ae8454d0b8b07eecccba5ecfe3b8f29ac38c42d612ebc9ac100a5faf8abebe57326f7c%26scene%3D21%23wechat_redirect) **|** **[名家经验](https://weibo.cn/sinaurl?u=http%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMjM5OTMwODM1Mw%3D%3D%26mid%3D2448069775%26idx%3D1%26sn%3Dfdec8da35cb54f3515ab1988e7030ebf%26chksm%3Db32349a18454c0b7e9c454ff7bbd02930605f08d3a70d21bd763b95cae7073bac0211c230345%26scene%3D21%23wechat_redirect)**

计量经济圈组织了一个计量社群，有如下特征： 热情互助最多 、 前沿趋势最多 、社科资料最多、社科数据最多、科研牛人最多、海外名校最多。因此，建议积极进取和有强烈研习激情的中青年学者到社群交流探讨，始终坚信优秀是通过感染优秀而互相成就彼此的。

![](https://r.sinaimg.cn/large/article/4b6fdb09e0c53ba89a44ffc2def4ff87)

![](https://r.sinaimg.cn/large/article/bd8096cf11cc5553f943e37fd4f63802)