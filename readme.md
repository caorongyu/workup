## 一起锻炼吧 (WorkUp)
---

#### 设计背景
* 社会高速发展，人们也越来越懒惰，生活压力也越来越大。减少疾病，延长寿命，放松心情最好的发放有两个，一个是**健身**，一个是**社交**。那么二者是否可以结合呢？？我们可以幻想一下未来有这样的场景。

* 工作狂姚晗，在办公室工作了一天，心情十分紧张。游戏狂车小宇，每天沉迷于游戏，神经紧绷。学习狂费鹏，在教室学了一天，是时候放松一下了，进行身体锻炼了。他们都拿出手机打开了我们的软件，**一起锻炼吧**。姚晗创建了下午5点的环湖跑的运动，费鹏通过附近活动搜索到并积极加入。车晓宇搜索到附近的好友费鹏，并且通过费鹏看到了他参加的活动环湖跑，于是一起加入进来。这样，他们通过我们的软件，集合到一起，一起享受**锻炼和社交的乐趣**。而这样从一个个零散的点汇聚成面，并且扩张。

---

#### 功能介绍

* **主界面**：现实头像，用户名和功能按钮。

* **创建活动**：用户可以作为发起人号召一个活动，设置活动的信息，还有活动的起点。

* **搜索活动**：用户可以作为参与人参加一个活动，他先通过搜索附近的活动获得附近活动的信息和地点，从中选择出自己喜爱的活动，并且可以加入该活动。

<img width="30%" height="30%" src="https://github.com/caorongyu/workup/blob/master/documents/pic/main_page.png">
<img width="30%" height="30%" src="https://github.com/caorongyu/workup/blob/master/documents/pic/create_act.png">
<img width="30%" height="30%" src="https://github.com/caorongyu/workup/blob/master/documents/pic/search_act.png">

* **开始活动**：发起好的活动和参加了的活动在活动开始前会发送推送提醒，这样保证用户不会错过每一个活动。如果在预订的时间内到达相应的地点，就可以看到参与这个活动的伙伴们了，这样大家聚集到一起，就可以开始活动了（这里我们会做活动地点和活动时间的判定，如果用户想投机取巧地在活动还没开始或者不在指定地点，是无法进行活动的）。活动过程中会有实时监控您的运动信息，记录时间，速度，路程，耗热量，耐力值，爆发力值，以及进行实时定位，用户会对此感觉到充满好奇。同时还会根据用户以往的锻炼经历进行提示，如还有多少米将到达您平均跑步的路程，更加人性化的人机交互会使得用户在锻炼过程中获得更多的乐趣。活动结束后客户端将整合好的数据发送给服务器，服务器会进行评分计算，并返回客户端，这里的评分将根据上述的信息以及参与的人数进行评判，用户可以与开始进行活动的伙伴PK，享受竞技的快感。而这些数据也是用户的最宝贵的资料，在服务器端进行分析。

<img width="30%" height="30%" src="https://github.com/caorongyu/workup/blob/master/documents/pic/start_act.png">
<img width="30%" height="30%" src="https://github.com/caorongyu/workup/blob/master/documents/pic/finish_act.png">
<img width="30%" height="30%" src="https://github.com/caorongyu/workup/blob/master/documents/pic/act_rote.png">

