# the_crew2-DR-
the crew2 按键精灵DR脚本，仅用于刷DR盐滩

开发环境：按键精灵2014  
运行环境：按键精灵8及以上

使用脚本前，请自行调整脚本1-4行的变量，变量意义已写入注释。  
脚本仅用于the crew2, DR, 盐滩赛事，且仅为配件等级全400调整，若配件等级低于400，需自行调整90-106行的Delay值。  
配件等级全400情况下，盐滩成绩稳定在13.0-13.2之间，满足大师等级要求13.5。  
屏幕分辨率不等于1920\*1080的，请自行调整87行的参数，调整方法为：FindColorEx 800, 350, 1080, 400,...调整为 FindColorEx (800/1920\*你的分辨率宽度）, （350/1080\*你的分辨率高度）, （1080/1920\*你的分辨率宽度）, （400/1080\*你的分辨率高度）,...  
脚本未在不同配置的电脑上测试，可能会受配置影响。

在开始脚本挂机之前，请清空总部邮箱，不然可能会损失配件和零件。  

在进入DR盐滩（请自行选择难度）并在比赛开始的three two one倒计时结束后按F1启动脚本，脚本会自动检测发车的绿灯，并自动完成升档、喷氮气操作。在比赛结束后会自动按N重新开始。  
在17局游戏后（若为双倍配件套则为9局），脚本自动返回总部并进入邮箱，若设置 if_clear_mailbox = 1 则自动清空邮箱（全部分解为零件），若设置 if_clear_mailbox = 0 则会弹窗并暂停脚本，清空邮箱后关闭邮箱界面并按空格键继续脚本。  
清空邮箱后脚本会自动进入DR盐滩。  
按F5结束脚本，结束后弹窗显示统计信息（可选）：运行时间（秒），进行的游戏数，清空邮箱次数

开始脚本后1分钟内未检测到绿灯会自动重新进入DR盐滩，连续运行4分钟未检测到绿灯会重新进入DR盐滩（DR比赛3分钟未完成会被自动踢出）


**_English Version:_**

the crew2 button wizard DR script, only used to brush DR salt flats

Development environment: Button Wizard 2014
Operating environment: Key Wizard 8 and above

Before using the script, please adjust the variables in lines 1-4 of the script yourself. The meaning of the variables has been written in the comments.
The script is only used for the crew2, DR, and Salt Flat events, and only the accessory level is adjusted to all 400. If the accessory level is lower than 400, you need to adjust the Delay value in lines 90-106 by yourself.

When the accessory level is all 400, the salt flat score is stable between 13.0-13.2, which meets the master level requirement of 13.5.

If the screen resolution is not equal to 1920*1080, please adjust the parameters of line 87 by yourself. The adjustment method is: FindColorEx 800, 350, 1080, 400,...Adjust to FindColorEx (800/1920 **X** your resolution width), (350/1080 **X** your resolution height), (1080/1920 **X** your resolution width), 
(400/1080 **X** your resolution height).

The script has not been tested on computers with different configurations and may be affected by the configurations.

Before starting the script and hang up, please clear the headquarters mailbox, otherwise you may lose accessories and parts.

After entering the DR salt flat (please choose the difficulty) and pressing F1 to start the script at the end of the three two one countdown at the start of the game, the script will automatically detect the green light of the start, and automatically complete the upshift and nitrogen spray operations. After the game is over, it will automatically restart by pressing N.

After 17 rounds of the game (9 rounds if it is a double accessory set), the script will automatically return to the headquarters and enter the mailbox. If you set **if_clear_mailbox = 1**, the mailbox will be automatically cleared (all broken down into parts), and if you set **if_clear_mailbox = 0**, it will play Window and pause the script, after clearing the mailbox, close the mailbox interface and press the space bar to continue the script.

After emptying the mailbox, the script will automatically enter the DR salt flat.

Press F5 to end the script. After the end, the pop-up window displays statistical information (optional): running time (seconds), number of games played, number of empty mailboxes.

After starting the script, if the green light is not detected within 1 minute, it will automatically re-enter the DR salt flat, and if the green light is not detected for 4 minutes, it will re-enter the DR salt flat (the DR game will be automatically kicked out if the DR game is not completed in 3 minutes)
