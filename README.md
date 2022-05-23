# AngelBeats - Catalog

* [AngelBeats - Readme(EN)](#angelbeats---readmeen)
  * [New Pills Coop](#new-pills-coop)
  * [Reason](#reason)
* [AngelBeats - Readme(中文)](#angelbeats---readmezh)
  * [新的药役](#新的药役)
  * [原因](#原因)
* [AngelBeats - Update logs(EN & 中文)](#angelbeats---update-logsen--zh)
  * [5.20 Update(EN)](#520-updateen)
  * [5.20 Update(中文)](#520-updatezh)
  * [4.26 Update(EN)](#426-updateen)
  * [4.26 Update(中文)](#426-updatezh)
  * [4.23 Update(EN)](#423-updateen)
  * [4.23 Update(中文)](#423-updatezh)
  * [4.20 Update(EN)](#420-updateen)
  * [4.20 Update(中文)](#420-updatezh)
  * [4.17 Update(EN)](#417-updateen)
  * [4.17 Update(中文)](#417-updatezh)
  * [4.15 Update(EN)](#415-updateen)
  * [4.15 Update(中文)](#415-updatezh)
  * [4.14 Update(EN)](#414-updateen)
  * [4.14 Update(中文)](#414-updatezh)

# AngelBeats - Readme(EN)
 
## New Pills Coop
> This is a new pills coop **based on `Zonemod`**.  
> ~~It uses **`Anne`'s _7-7_ plugin** to spawn infected.~~ Now it uses my own plugin to do so.  
> It **looks like `Ast` but more difficult than `Ast`**.  
> ~~It likely won't spawn infected if survivors can see them, but because of anne, it will teleport infected, so maybe TP on your face?? XD.~~ It will nerver spawn on your face, **NEVER!!**  

## Reason
> I made this coop because `AnneHappy` is **unfriendly** to survivor since _11-28_ plugin.  
> `AnneHappy` now spawn infected in an **_unfriendly way_**, such as spawn **on your face** or **on your back** etc.  
> **Hard is needed**, but **_not in this way_**. That's why I made `AngelBeats`.

# AngelBeats - Readme(ZH)
 
## 新的药役
> 这是一个 **基于 `Zonemod`** 的新药役.  
> ~~它使用了 **`Anne`的 _7-7_ 插件** 来生成特感.~~ 现在是使用我自己的插件实现特感生成了.  
> 它看起来 **很像 `Ast` 但比它更难**.  
> ~~它不太可能会直接刷新到你脸上，但是由于`Anne`的插件有**传送机制**，所以有可能TP到生还脸上??XD.~~ 它绝对不会和`Anne`一样刷新到你脸上，TP也不会.  

## 原因
> 我制作这个药役的原因是 `AnneHappy` 自 _11-28_ 后对生还**极不友好**.  
> `AnneHappy` 现在生成特感 **_以一种极端的方式_**, 例如 **贴脸刷** 或者 **转身刷** 等等.  
> **难度很有必要**, 但 **_不应该是这样_**. 这就是我制作 `AngelBeats` 的原因.  

# AngelBeats - Update logs(EN & ZH)
## 5.20 Update(EN)
> Attention! This is a **huge UPGRADE**, so you need to **delete some files** because it's never used, see it at followed.  
> > 1. I suggest you to **delete the 'plugins' folder** and **put the new 'plugins' folder** as replaced. If you **add you own settings**,  **remove the 'anne' folder** which is in the 'angel' folder, then **do the replace** as before.  
> > 2. Delete the 'hostname.smx' file in the 'angel'.  
> 
> The **UPGRADE** is as followed:  
> > 1. The `anne`'s InfectedSpawner plugin has been fully removed. Now I use my own Director to control the infected spawned.  
> > 2. Add the spawn info to the hostname.  
> > 3. Fixed the melee not spawn as expect.  
> > 4. Fixed the incorrect survivor count when someone joined.  
## 5.20 Update(ZH)
> 注意！这是一次**大更新**，所以你需要删除部分文件因为这些文件将不再被使用，不删除将导致特感刷新异常！详情见下方：  
> > 1. 我建议你先删除'plugins'文件夹然后再使用新的'plugins'文件夹替换，如果你添加了自己的插件，删除'angel'文件夹中的'anne'文件夹，然后再做全局替换  
> > 2.删除'angel'文件夹中的'hostname.smx'这个插件  
> 
> 本次**更新**了如下内容：  
> > 1. 删除了`anne`的刷特插件，改为使用我自己的Angel导演插件控制刷新  
> > 2. 在服务器名称中添加了当前的刷特信息  
> > 3. 修复了出门不会给予砍刀的bug  
> > 4. 修复了玩家加入生还时，生还的人数错误问题  
## 4.26 Update(EN)
> Separate the training mod from director plugin.  
> Mixed the refill plugin with training plugin.  
> Add a creator plugin.  
> Add all4dead2 support.  
> Test training plugin(It was coded with objected-pawn grammar, see a [test example](https://github.com/PaimonQwQ/L4D2-Plugins/tree/main/Object-Pawn%20Plugins%20TEST#readme) in my L4D2-Plugins repo).  
## 4.26 Update(ZH)
> 将训练模式从导演插件中分离  
> 将自动装填插件与训练模式插件融合  
> 添加了造物主插件  
> 添加了All4Dead2插件  
> 测试训练模式插件(训练模式是用仿面向对象的语法风格编写，详情见我L4D2-Plugins仓库中的一个[测试用例](https://github.com/PaimonQwQ/L4D2-Plugins/tree/main/Object-Pawn%20Plugins%20TEST#readme))  
## 4.23 Update(EN)
> Add Training Mode, you can choose whatever you want in vote.  
> Add re-health vote, now you can get temp health by kill infected.  
> Fixed dmg taken for single player, now temp health will decrease correctly.  
> Fixed player will be kill by plugin when player's real health is lower than 2.  
> When tank is in play and the survivor count is less than 4, SI's count will be less than half of the limit in the party mode.  
## 4.23 Update(ZH)
> 添加了训练模式的投票，你现在可以在投票中选择想要在训练中获得的增益了  
> 添加了回血投票， 开启回血后可以通过杀死特感获得虚血  
> 修复了单人时的受伤bug，虚血可以被正确的减少了  
> 修复了插件在玩家实血低于2滴血时自动处死玩家的bug  
> 在派对模式中，如果Tank已经生成，并且生还玩家数量少于4，则特感刷新数量减半，直至Tank死亡  
## 4.20 Update(EN)
> Fixed shove times to 5.  
> Add a plugin that allows player to auto-refill, needs vote to turn on.  
> Add training mode that makes 1vht mode more easier, needs vote to turn on.  
> Change the jockey-skeet dmg to 170(former is 195) and fixed the hunter-skeet dmg to 150.  
> Change the shotgun limit to 3.  
> Open all talk.  
> Allow all bot gaming.  
> Change the smoker self-clear dmg to 170(former is 200).  
## 4.20 Update(ZH)
> 修正了生还推的次数为5  
> 增加了一个插件允许玩家的武器可以自动装填，需要投票开启  
> 新增了训练模式，在1vht时降低扣血，需要投票开启  
> 修改了Jockey被空爆的伤害为170(之前是195)，修复了Hunter被空爆的伤害为150  
> 喷子的数量限制修改为3  
> 默认开启了全语音  
> 修复了提示需要双方均有人参与的bug  
> 修改了舌头自救的伤害为170(之前是200)  
## 4.17 Update(EN)
> Fixed Spec-Hud to show the state of tank.  
> Updated the MVP info, added more statistics MSG.  
> Add a vote allows player to use infinite shoved.  
> Fixed the bug that when server is empty, the timer was still count down.  
> Add a vote allows player turn off the consume-tank(default on).  
## 4.17 Update(ZH)
> 修复了旁观视角的TankHud  
> 升级了Mvp的技术信息统计，添加了章节时长和重启次数  
> 添加了一个投票，允许玩家使用无限推，用于训练枪法  
> 修复了Mvp的章节时长在空服时继续计时的问题  
> 添加了一个投票，允许玩家决定是否开启消耗克(默认开启)
## 4.15 Update(EN)
> Fixed the plugin's URL.  
> Update the latest AI-Tank-Enhance plugin.  
> Change the tank consume times to 1.  
> Change the tank suffered damage percent to 100.  
> Add a Save-Chat plugin.  
> Fixed Spec-Hud plugin's error report cause by Pause plugin is missing.  
## 4.15 Update(ZH)
> 修正了插件的项目链接  
> 升级了Tank增强插件为最新的消耗克插件  
> 修改克消耗最大次数为1  
> 修改克消耗受到伤害比例为100%  
> 新增了一个插件用于保存聊天记录，方便查证  
> 修复了Tank面板因为缺少Pause插件的引用而产生的报错  
## 4.14 Update(EN)
> Add a plugin and a vote that allows player to choose which type of infected she wanna player with.  
> Weaken the tank when playing charger or jockey party.  
> Fixed player self-save times when survivor count is lower than 4.
## 4.14 Update(ZH)
> 添加了特感派对的插件，使用!vote进行选择  
> 削弱了ChargerParty和JockeyParty中的tank  
> 修复了玩家在4人以下时的解控次数错误问题  
