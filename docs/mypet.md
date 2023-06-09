##  🪝 捕捉宠物
### 第一次捕捉

+ 手里拿着栓绳，打死你想要捕捉的生物即可

### 后续捕捉

如果你已经抓过宠物了，你需要先使用`/petstore`指令将你的宠物存在仓库里，然后你才能再抓一只

### 无法捕捉的宠物

1.末影龙(监测末影龙的行动会消耗很大的服务器性能)

2.恶魂(原因不明，默认是关闭)

3.凋零(原因不明，默认是关闭)

## ⚔️ 宠物技能

> [!warning]
宠物技能只能选择一次，请务必提前了解各种技能

在捕捉宠物后使用`/pcst`进行技能树选择

选择后可以通过`/petskill`查看技能进度

<!-- tabs:start -->

#### **荆棘坦克**

防御型技能树(初始攻击2):

 + 每级宠物自身提高1.5生命值+0.2近战伤害

 + 每2级宠物增加1%荆棘触发概率和1%反伤效果

 + 30级解锁信标Buff: 伤害吸收;抗性提升;生命恢复

 + 60级升级信标Buff为2级(最多使用2个)

 + 90级升级信标Buff为3级(最多使用3个)

 + 50级额外解锁骑乘

#### **兔子骑士**

骑乘型技能树(初始攻击1):

 + 每级宠物自身提高0.5生命值+0.1近战伤害

 + 1级解锁骑乘，每级增加1%骑乘速度

 + 30级解锁信标Buff: 速度;跳跃提升

 + 60级升级信标Buff为2级(最多使用2个)

 + 90级升级信标Buff为3级(最多使用2个)

 + 80级额外解锁骑乘飞行

#### **火焰战士**

攻击型技能树(初始攻击4):

 + 每级宠物自身提高1生命值+0.4近战伤害

 + 每2级宠物增加1%引燃概率，引燃持续3秒

 + 30级解锁信标Buff: 力量；防火

 + 60级升级信标Buff为2级(最多使用2个)

 + 90级升级信标Buff为3级(最多使用2个)

 + 50级额外解锁骑乘

#### **元素法师**

法术型技能树(初始攻击2):

 + 每级宠物自身提高0.6生命值+0.1法术伤害

 + 30-60级解锁冰霜，每级增加1%减速概率，减速持续3秒

 + 60-90级解锁火焰，每级增加1%点燃概率，点燃持续3秒

 + 90-100级解锁凋零，每级增加1%凋零概率，凋零持续3秒

 + 50级额外解锁骑乘


#### **雷霆射手**

远程型技能树(初始攻击3):

 + 每级宠物自身提高0.8生命值+0.1远程伤害

 + 每5级宠物增加2次射击/分钟(不是很准确)

 + 40-100级解锁三叉戟(原先射的是箭)

 + 40-100级,每3级增加1%引雷概率，增加1点雷击伤害

 + 50级额外解锁骑乘

#### **黄金矿工**

挖矿型技能树(初始攻击2):

 + 每级宠物自身提高0.3生命值+0.1近战伤害

 + 每2级宠物增加1%击退概率

 + 30级解锁信标Buff: 夜视;急迫

 + 60级升级信标Buff为2级(最多使用2个)

 + 90级升级信标Buff为3级(最多使用2个)

 + 50级额外解锁骑乘

<!-- tabs:end -->

## 🏆 宠物升级

+ 宠物满级为100级
+ 宠物能被动获得主人25%的经验
+ 可以使用/petinfo查看宠物的等级和升级所需的经验值


## 🍖 宠物饥饿

+ 宠物的饥饿值上限为100，最低为1。
+ 宠物复活的时候是根据饥饿值决定生命值的 
 |     饥饿值    |      生命值     | 
 | :------------| :----------------|
 | 100-91| 满血| 
 | 90-81| 90%最大生命值| 
 | 90-81| 90%最大生命值| 
 | 80-71| 80%最大生命值| 
 | 70-61| 70%最大生命值| 
 | 60-51| 60%最大生命值| 
 | 50-41| 50%最大生命值| 
 | 40-31| 40%最大生命值| 
 | 30-21| 30%最大生命值| 
 | 20-11| 20%最大生命值| 
 | 10-2| 10%最大生命值| 
 | 1| 1点生命值| 

+ 宠物饥饿值为1时，宠物将不断掉血到1点生命值
+ 宠物饥饿值为100时，继续喂食宠物，没电饥饿值会恢复6点生命值
+ 宠物骑乘也会每格会消耗0.01的食物，低饥饿值会影响宠物的骑乘速度
+ 宠物信标也会消耗食物(具体多少不清楚)，低饥饿值会影响信标光环的范围

## 📕 指令大全
> `/mypet`   
> + 打开服务器的原版宠物菜单

> `/petinfo`   
> + 显示宠物的信息
>  + 血量
>  + 饥饿值
>  + 食物
>  + 行为
>  + 等级
>  + 经验值

> `/petname`
> + 重新设置宠物名字     
> + 用法示例
>   + /petname &a无敌僵尸王
> + 只支持原版颜色代码 
> 
> ![颜色](pics/mypet/color.png)

> `/petrelease`
> + 放生宠物<font color=red>(注意：你将完全失去这个宠物)</font>

> `/petcall`
> + 传送宠物过来
> + 指令简写: `/petc`

> `/petsendaway`
> + 把你的宠物送走
> + 你仍然可以试用`/petcall`指令将它召唤回来
> + 指令简写: `/psa`

> `/petrespawn`
> + 用法: `/petrespawn [pay 或 show 或 auto]`
> + 使用 `/petrespawn pay` 可以支付一定的费用让宠物复活
> + 使用 `/petrespawn auto 10`,比如你的宠物复活时间有16秒，那么会在最后10秒的时候支付费用让他复活
> + 指令简写: `/pr`

> `/petswitch`
> + 打开宠物仓库，更换你的宠物
> + 指令简写: `/pswitch`

> `/petstore`
> + 将你当前的宠物存储在仓库里
> + 你可以用`/petswitch`指令召唤被存储的宠物
> + 如果你当前有宠物了，你需要使用这个指令存储宠物再继续抓
> + 指令简写: `/pswitch`

> `/petchooseskilltree`
> + 选择你的宠物技能(具体查看[宠物技能](#⚔%ef%b8%8f-宠物技能)章节)
>   + 荆棘坦克
>   + 兔子骑士
>   + 火焰战士
>   + 元素法师
>   + 雷霆射手
> + 指令简写: `/pcst`

> `/petskill`
> + 显示你宠物的技能
>   + 技能伤害
>   + 血量
>   + 行为模式
>   + 信标

> `/petstop`
> + 让宠物停止攻击
> + 在打野(farm)和主动(aggressive)行为模式下，这个指令没用

> `/petbehavior`
> + 切换宠物的行为模式
> + 具体用法: /petbehavior [模式]
>   + normal  ->正常模式: 像狼一样，攻击主人的目标以及保护主人
>   + friendly  ->友好模式: 宠物永远不会攻击(即便被打了)
>   + raid  ->突袭模式: 和正常模式一样，但不会攻击玩家和宠物
>   + duel  ->决斗模式: 会攻击5格内决斗模式的宠物
>   + farm  ->打野模式: 攻击15格内的所有怪物
>   + aggressive  ->主动模式: 攻击15格内的所有生物
> + 指令简写: `/pb`

> `/petbeacon`
> + 打开宠物信标光环的菜单
> + 指令简写: `/pbeacon`
## ❓ 常见问题

### 无法捕捉宠物|抓不了宠物

+ 你需要使用栓绳攻击生物，用铁砧改名后的栓绳不行
+ 你已经有宠物了，你需要先用/petstore存储当前的宠物再抓
+ 末影龙，恶魂，凋零是无法捕捉的

### 抓的宠物不见了

+ 是否被自动保存到宠物仓库里去了?使用`/petswitch`查看
+ 宠物是否死亡了？输入`/petinfo`查看宠物信息

### 宠物持续掉血
+ 宠物饿了，需要吃东西，输入`/petinfo`查看它的食物，右键喂养它

### 宠物无法骑乘
+ 宠物饥饿值降为1后将无法骑乘
+ 除了兔子骑士技能树可以1级解锁骑乘外，其他技能需要50级解锁骑乘
+ 需要使用栓绳右键宠物来骑乘
+ 原版的马、羊驼等能骑乘的宠物在捕捉后也会失去原版的骑乘效果

### 宠物无法飞行
+ 原版能飞行的宠物在捕捉后都会失去飞行能力(强制使用狼的AI)
+ 需要选择兔子骑士这个技能树，升级到80级后用栓绳右键它骑乘

### 宠物装备
+ 有些生物能装备物品、盔甲等等。比如女巫能手持物品，猪灵、僵尸、骷髅能穿盔甲
+ 需要手里拿着物品，蹲着右键宠物给它穿上
+ 如果想取下装备，可以使用剪刀右键它