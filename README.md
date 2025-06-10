# Elden-Ring-Nightreign-Cheat-Table | 《艾尔登法环 黑夜君临》简易CT
A simple self-made Cheat Table (CT), free to use as reference; currently being updated.

自行制作的简易ct，可以随意借鉴，目前正在更新中

# Entries | 修改条目
**WARNING** In version 1.01.2 this entries are out of date. | 在新版本1.01.2中，这些地址已无效
 * Rune | 卢恩（局内魂）
 * Murk | 夜痕（局外魂）
 * Hp/MaxHp | 生命/最大生命
 * FP/MaxFP | 专注值/最大专注值
 * Stamina/Max Stamina | 耐力/最大耐力

# Possible Reliable Environment | 可能运行环境
 I tested this CT in | 此CT测试于
  * win 11
  * Elden Ring Nightreign version 1.0.2
  * Cheat Engine 7.5

# DIARY

**25/6/10**  
I have found instructions(addresses) associated with opneing Sparring Equipment menu in the training area. Using ultimap2.  
找到了与打开训练场更换装备菜单有关的指令地址  
 * nr.exe+137E05C
    > Break point hitted when opening Sparring menu, opening other menu will not hit.  
    > 当打开装备选择菜单时，此地址命中断点，打开其它菜单不会
 * nr.exe+137DEA0
    > Break point hitted before F interation tip emerged or changed, or opening not only Sparring menu.
    > 在打开包括其它菜单或F交互提示框变动时，命中断点

**More Infomations**
When opening Spparring menu, the break point hitting sequence is nr.exe+137DEA0(once)->nr.exe+137E05C->nr.exe+137DEA0(several times)->openMenu
