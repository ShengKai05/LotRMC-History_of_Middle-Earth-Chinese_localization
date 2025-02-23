# LotRMC-History_of_Middle-Earth-Chinese_localization

本仓库为中洲历史模组（History Of Middle-Earth-1.7.10）的汉化仓库，是中洲历史模组的官方汉化。

中洲历史模组是我的世界[魔戒模组](https://www.mcmod.cn/class/211.html)的附属模组，详细介绍请查看MC百科页面：[[HoME]中洲历史：传承](https://www.mcmod.cn/class/12119.html)

## 魔戒MC中文社区
该汉化项目属于魔戒MC官方中文社区，是一个面向MC魔戒玩家的中文官方交流群。

社区内有着关于魔戒的所有资源，且入驻有国内所有魔戒大型服务器。

欢迎前来讨论魔戒与进行文创，下载官方汉化Mod、整合包、手机端、建筑包以及其他资源，浏览国内魔戒服务器，参与汉化、整合、wiki编辑、资源分享等。

群号：973932359

## 仓库构成：
**lang** 文件夹内是语言文件，是Minecraft中的本地化文件，用于将游戏中的文本翻译成不同的语言，除了魔戒自己设计的NPC姓名、对话、小任务系统，与外置的NBT信息之外，其他所有内容都在lang文件里。

**neme** 文件夹是魔戒NPC的姓名。

**speech** 文件夹是魔戒NPC的对话，以及NPC小任务。

# 参与汉化
## 汉化须知
作为译者，就要严谨，自己不确定的就不要做，与他人讨论最终敲定了再修改。

汉化的内容需要客观精准，严禁纯机翻以及私自添加整活内容，宁愿汉化不完，也不要粗略翻译。

这个汉化项目是在线团队项目，每个人都可以来在线修改，若自己时间有限可以邀请更多人参与翻译。

### 翻译标准
需要严格检查专有名词的译名，按照[MC魔戒中文Wiki](https://lotrmc.huijiwiki.com/wiki/%E9%A6%96%E9%A1%B5)翻译，例如“索隆”，不可以写成“索伦”。

MC基础物品的翻译，应该按照原版MC中的物品命名格式来翻译，可以参照[中文Minecraft Wiki](https://zh.minecraft.wiki/)。例如“榆木木板”，不能翻译成“榆木板”，参考“橡木木板”。

魔戒模组中的常见名词，应该按照传承版译名表，例如“前哨站(Outpost)”不能写成“哨所”，“屠夫(Butcher)”不能写成“肉贩”。

用语方面也应该延续传承版的格式，例如传承版里的盔甲成就描述是“装备整套xxx盔甲”，就不能写成“整备全套的xxx铠甲”；传承版的击杀成就是“xxx杀手”，就不能写成“杀xxx者”。

### 填写改动说明
这是一个团队项目，做任何事前，都要先考虑一下其他人能否看懂你做了什么，并接着你继续汉化下去。必须认真填写改动说明(Commit Summary)，严禁随意填写。

每编辑一类改动，就要做一个提交。不要把所有的改动都放在同一个提交里，那样真的很难让人一眼看明白你提交了什么！

如果每个改动之间没有联系，那就应该都单独提交。如果一些改动属于修改了同一类的内容，那它们就可以写在一起，不过具体的每条改动都要写在描述里。

### 改动说明的格式
要让人一目了然，简洁易懂。

改动分为以下几种：汉化、润色、重译、修正、更改。

润色与重译，一般用于对话和小任务等长句子的改动，区别是：**润色**是感觉原对话与英文大差不差，只是有点不合中文用语习惯；而**重译**是曲解了原英文对话的含义，不得不从头重新翻译。

修正与更改：一般用于lang文件里的某个词语的改动，区别是：**修正**是某个词很明确是错译，没有按照邓版翻译，或者不符合传承版的译名表与用语格式；而**更改**是原翻译没有大问题，只是调整为一个更好的译名。

这些改动还需要为改动的对象分类，保持分类整齐即可，一般有以下的对象分类：物品名、方块名、生物名、成就名、路径点名、建筑名、生物群系名等，如果是大规模改动某个词语，不好分类，可以直接称为“名词修正”、“译名修正”。

改动说明的格式也需要简洁清晰，需要使用动宾短语，禁止随意填写，以下是几个范例：

>译名修正，所有的“索伦”改为“索隆”
>
>生物名修正，所有的“肉贩”改为“屠夫”
>
>头衔名修正，多温尼安的“葡萄工”改为“葡萄农”
>
>成就更改，“维拉的使者”改为“维拉的密使”
>
>对话重译，鲁德尔投火手的友好、中立、敌对对话重新翻译。
>
>对话润色，刚铎塔卫的对话润色。
>
>小任务润色，蓝山矮人的所有的小任务润色。

### 汉化工具与技巧
禁止使用国内的翻译软件与平台，例如百度、有道等。

单个词语把握不准时，要使用[剑桥词典](https://dictionary.cambridge.org/zhs/)，能够查询到该单词所有详细的释义。

翻译长文本时，必须至少尝试用[DeepL](https://www.deepl.com/translator)翻译一遍，其它翻译可能会出现语法问题，而DeepL基本没有语法问题，符合中文用语习惯。

最佳方案是使用[ChatGPT](https://chat.openai.com/chat)，已经没有对国内的注册限制，可以随意注册使用。

科学上网推荐使用[EEVPN](https://www.55jiasu.com)，一整年才15元，没有限速，每个月限用15G流量，不看视频绰绰有余。

### 汉化进度
目前speech文件夹、name文件夹已经完成汉化但仍需校对，lang文件3.38版本完成60%的进度，其他版本暂未取得进度，汉化文件下载还暂请使用3.38版本的zh_CN.txt(使用时请删去文件名中版本号)
