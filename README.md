# FFxivPythonCheat

<!-- 引入 Font Awesome 图标库 -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
[<i class="fa-brands fa-discord"></i> 点击加入 Discord 服务器获取脚本更新资讯](https://discord.gg/sQYu5CkH)

```
███████╗██╗   ██╗ ██████╗██╗  ██╗    ███████╗███████╗██╗  ██╗██╗██╗   ██╗
██╔════╝██║   ██║██╔════╝██║ ██╔╝    ██╔════╝██╔════╝╚██╗██╔╝██║██║   ██║
█████╗  ██║   ██║██║     █████╔╝     █████╗  █████╗   ╚███╔╝ ██║██║   ██║
██╔══╝  ██║   ██║██║     ██╔═██╗     ██╔══╝  ██╔══╝   ██╔██╗ ██║╚██╗ ██╔╝
██║     ╚██████╔╝╚██████╗██║  ██╗    ██║     ██║     ██╔╝ ██╗██║ ╚████╔╝ 
╚═╝      ╚═════╝  ╚═════╝╚═╝  ╚═╝    ╚═╝     ╚═╝     ╚═╝  ╚═╝╚═╝  ╚═══╝   


 ██████╗ ██████╗ ███████╗███████╗███╗   ██╗██████╗ ██╗      █████╗ ██╗   ██╗███████╗██████╗ 
██╔════╝ ██╔══██╗██╔════╝██╔════╝████╗  ██║██╔══██╗██║     ██╔══██╗╚██╗ ██╔╝██╔════╝██╔══██╗
██║  ███╗██████╔╝█████╗  █████╗  ██╔██╗ ██║██████╔╝██║     ███████║ ╚████╔╝ █████╗  ██████╔╝
██║   ██║██╔══██╗██╔══╝  ██╔══╝  ██║╚██╗██║██╔═══╝ ██║     ██╔══██║  ╚██╔╝  ██╔══╝  ██╔══██╗
╚██████╔╝██║  ██║███████╗███████╗██║ ╚████║██║     ███████╗██║  ██║   ██║   ███████╗██║  ██║
 ╚═════╝ ╚═╝  ╚═╝╚══════╝╚══════╝╚═╝  ╚═══╝╚═╝     ╚══════╝╚═╝  ╚═╝   ╚═╝   ╚══════╝╚═╝  ╚═╝

 ```                                                                                        
ACT 不算开？卫月不算开？哟呵，那些个自诩只开不影响游戏平衡的插件的绿色玩家
还有号称只捣鼓游戏模组的黄色玩家，可真是太 “可爱” 啦！您瞧瞧，他们一边大义凛然地宣称自己的所作所为毫无不妥
一边堂而皇之地利用着这些所谓 “不影响平衡” 的东西，在游戏里横冲直撞，这脸皮厚度，简直比城墙拐弯还厚呐。
要是真不影响平衡，咋不见他们在公平竞技的纯原生游戏环境里，靠着真本事打出一片天呢？
每次被质疑了，就拿 “插件和模组无害” 当挡箭牌，糊弄谁呢？真是搞笑了。

## 在Releases处下载最新构建后 直接运行里面的BAT即可。
- GrandCompany()    无视军衔交军票
- ShopQuantity()    解除购买量限制(新版本游戏内置)
- MovePermission()  强制移动
- AntiKnock()       防鸡腿
- GetActionRange()  技能距离增加
- NoBackswing()     技能后摇可移动(LB后摇)
- Speed()           移速
- PassWall()        穿墙
- ExecuteCommand()  执行命令
- AnimLock()        动画锁
- Campeng()         相机碰撞
- FallCheckPatch()  部分副本无坠落
- NoRender()        禁止渲染
- NoActionMove()    技能无突进位移
- SendPacket()      监听客户端发送的数据包
- CastingMoveable() 在角色读条时屏蔽发送的移动数据包实现读条移动(本质在读条期间还是原地不动)

### 老子就是要开挂，就是要作弊！ 那些自认为清高的所谓 “绿色玩家” “黄色玩家” 真是死妈妈了，真让人难以理解。明明就他妈的属于外挂性质的东西，轻描淡写地用 “插件” 一词带过。你觉得游戏有提供这些相关的 API 接口吗？你们现在所使用的哪一样不是违反游戏规则的？就拿某某月说的那样`啊啊，我认为这些是相对安全的，只要你仅使用官方库的 xxx`这不是给违规行为开绿灯吗？臭不要脸倒贴上赶着脱裤子撅屁股的贱样，还有“黄色玩家” 们，你们真的像自己所宣称的那样没有过度使用吗？就纯鸡巴贱。
### 玩玩游戏 MOD 就算了，可你们非要跳出来强调立场，还说什么开挂的死妈，先审视下自己的行为是否真的合规吧，真的搞笑了，你们自己死不死妈妈吧。以及，本来就是开源开放的东西，别人做了第三方的感觉威胁到自己的领地了，嗷嗷开始反对这个反对那个`你们用你们的外挂月去，我们这个是绿色月` 怎么不去死呢？你妈生你的时候是不是在上厕所，导致你现在满脑子的屎不会思考了？咋地你妈会有丝分裂？外挂月又是怎么定义的呢？绿色月又绿色到哪里去了呢？想不通啊，是不是到时候再建立一个独立的服务器你到时候也要跳脚说那是外挂服我们这个是绿色服！就你们这些鸡巴玩意就和他妈的和Souma坐一桌子。没脑子还死爱装，秋水都比你们强，我说的。哦不对，你们这种立牌坊的婊子就纯纯你浪费你爸妈那十分钟，闲得慌喜欢瞎几把冲浪就多看看天空，你妈可能在看你。
### 讨厌开挂的人，那我就在这里给所有的基础外挂源码都发出来。全民大开挂，就讨厌你们这种`爱立牌坊的婊子`,纯死妈。日过你妈逼的生物种类比二维码还要丰富。
### 再次声明，以上言辞虽激烈，但仅针对部分在游戏插件使用问题上言行不一、强词夺理之人。我充分理解插件开发者在维护插件过程中投入的心血与成本，也明白合理合法的插件存在的价值。在此郑重澄清，此番表达绝非针对插件本身，更无意损害任何正当经营或合理使用插件群体的合法权益，仅仅是希望相关人员能正视自身行为，避免在游戏环境中引发不必要的争议与混乱。
``“如果词不达意你看不懂的话，我就空降你妈红红火火的葬礼 先把你等上菜全家老小 用你妈剩下的批水活活淹死 再扯下灵堂白布在你妈坟头用音响放首《祝你平安》 祝她忌日快乐 再回来帮你这个下贱的无脑孤儿擦擦眼泪。”``
### 这游戏当土皇帝成本真低，是不是就是看不得别人用非你们认证的插件呢？你知道对应的开源协议是什么吗？挂什么时候也有三六九等了，想要只手遮天了？你自己那点生平事迹平日里都做了啥别以为别人不知道，自己没点本事就来当土皇帝了？我觉得某个东西也不能一直在传什么怪的东西吧。不会哪天发疯了 整个超大压缩包Excel发石之家吧？我记得之前也被人骂过来着，好了伤疤忘了疼，被人骂的哭唧唧找妈妈现在来这里找存在感当土皇帝了是吧？
