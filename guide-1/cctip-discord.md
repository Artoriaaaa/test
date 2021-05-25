# CCTip @Discord

请认准 Discord 官方 CCTip 账号：CCTip Bot\#0897

## 充值

#### 方式一：私信 CCTip Bot 进行充值

私信 CCTip Bot，发送 “**deposit ETH**” ，CCTip Bot 将回复你的专属 ETH 充值地址。使用你的钱包向该地址转账 ETH，达到一定的确认数之后，CCTip Bot 将为你入账。

充值其他币种，请将指令中的 ETH 换成其他币种符号。

#### 方式二：在 My CCTip 中充值

以充值 ETH 为例，用自己的 Discord 账号登录 [my.cctip.io](https://my.cctip.io/), 进入“**Balance-&gt;ETH**”页面，点击“**Deposit**”，你将看到你的专属 ETH 充值地址。使用你的钱包向该地址转账 ETH，达到一定的确认数之后，CCTip 将为你入账。

充值其他币种，请将指令中的 ETH 换成其他币种符号。

不同币种入账所需的条件如下：

* ETH & ERC20 : 12 个确认数 
* BCH & SLP ： 2 个确认数
* BTC ： 2 个确认数   
* TRX：状态为已确认
* DOGE ： 10 个确认数 
* LTC ： 5 个确认数
* BSV ： 2 个确认数
* DASH ： 6 个确认数
* ZIL ： 6 个确认数

## 余额查询

#### 方式一：私信 CCTip Bot 查询余额

私信 CCTip Bot ，发送 “**Balance**” ，CCTip Bot 将回复你的账户余额。

#### 方式二：在 My CCTip 中查询

用自己的 Discord 账号登录 [my.cctip.io](https://my.cctip.io/), 进入“**Balance**”页面，查询余额。

## 提现

#### 方式一：私信 CCTip Bot 提现

以将 1.01 个 BTC 提现到 17Ui3e2cnwb13cdWxASBHsC6qZ56YKj3gj 为例。

私信 CCTip Bot ，发送 “**withdraw 1.01 BTC 17Ui3e2cnwb13cdWxASBHsC6qZ56YKj3gj**” ，如果你的余额足够，CCTip Bot 将处理你的提现请求，并在 10 分钟内汇出。

提现时，请根据你的提现需求替换指令中的数量，币种，地址等信息。

#### 方式二：在 My CCTip 中提现

以将 1.01 个 BTC 提现到 17Ui3e2cnwb13cdWxASBHsC6qZ56YKj3gj 为例。

用自己的 Discord 账号登录 [my.cctip.io](https://my.cctip.io/), 进入“**Balance-&gt;BTC**”页面，点击“**Withdraw**”，输入提现金额 1.01, 在提现地址输入 17Ui3e2cnwb13cdWxASBHsC6qZ56YKj3gj，完成验证后，CCTip 将处理你的提现请求，并在 10 分钟内汇出。

#### 不同币种所需的提现费用不同，如下：

* ETH & ERC20 : 根据链上情况实时波动变化
* BCH：0（当日有 2 次免费提现次数，次数使用完收取 0.0001 BCH/次）
* BTC：0.0003 BTC
* SLP: 0.0002 BCH
* TRX&TRC10: 0.5 TRX

  TRC20: 5 TRX

* DOGE：2 DOGE
* LTC: 0.0002 LTC
* BSV：0（当日有 2 次免费提现次数，次数使用完收取 0.0001 BSV/次）
* DASH：0.0002 DASH
* ZIL：0.004 ZIL

## 红包雨

如果你想随机给频道内的用户发红包，炸出更多潜水用户，鼓励他们更加积极活跃参与讨论，可以使用红包雨指令。

以 “cc rain 1 BTC 100” 为例，在频道中发送该指令会开始挥洒红包雨。

该红包雨的规则是：随机给频道内 100 个幸运儿发红包，每人获得 0.01 BTC。

指令格式：

> cc rain 代币数量 代币符号 红包雨人数

## 创建空投

创建空投即可以将你喜爱的代币发送给更多的人，也可以增加频道的活跃度。

在频道中创建空投仅需 2 步：

1. 充值

   向你的账户充值足够的币

2. 拉 @CCTip Bot\#0897 进频道

   在频道中加入 @CCTip Bot\#0897，并输入创建空投指令。

#### 1.创建一个空投 <a id="toc197"></a>

以 “ **cc airdrop 1 BTC 100** ” 为例，在频道中发送该指令会创建了一个空投。

该空投的规则是：接下来在频道内发送 “ **grab** ” 的前 100 人将每人获得 0.01 个 BTC。

指令格式：

> cc airdrop TokenAmount TokenSymbol NumberOfPeople

#### 2.创建一个带口令的空投 <a id="toc198"></a>

若你希望发言内容必须满足一定要求才能领取空投，你可以创建带口令的空投。

以 “ **cc airdrop 1 BTC 100 \#BTC\_to\_da\_moon** ” 为例，在频道中发送该指令会创建了一个带口令的空投。

该空投的规则是：接下来在频道里发送 “ **\#BTC\_to\_da\_moon** ” 的前 100 人，将每人获得 0.01 个 BTC。

指令格式：

> cc airdrop TokenAmount TokenSymbol NumberOfPeople \#keywords

#### 3.创建一个金额随机空投 <a id="toc199"></a>

如果你希望每个人领取到的金额不同，可以创建一个随机空投。

以 “cc draw 1 BTC 100” 为例，在频道中发送该指令会创建了一个金额随机空投。

该空投的规则是：接下来在频道内发送 “ **grab** ” 的前 100 人，将会共同瓜分 1 BTC，每人获得的金额随机。

指令格式：

> cc draw TokenAmount TokenSymbol NumberOfPeople

#### 4.创建一个带口令的金额随机空投 <a id="toc200"></a>

如果你希望每个人领取到的金额不同，并且发送某个关键词才能领取空投，可以创建一个带口令的金额随机空投。

以 “ **cc draw 1 BTC 100 \#BTC\_to\_da\_moon** ” 为例，在频道中发送该指令会创建一个带口令的金额随机空投。

该空投的规则是：接下来在频道里发送 “ **\#BTC\_to\_da\_moon** ” 的前 100 人，将会共同瓜分 1 BTC，每人获得的金额随机。

指令格式：

> cc draw TokenAmount TokenSymbol NumberOfPeople \#keywords

## 领取空投

#### 领取普通的空投 <a id="toc202"></a>

普通的空投不带口令，例：“ **cc airdrop 1 BTC 100** ” 和 “ **cc draw 1 BTC 100** ”。

你只需在频道里发送 “ **grab** ” 后，将能领取币。

#### 领取带口令的空投 <a id="toc203"></a>

以 “ **cc airdrop 1 BTC 100 \#BTC\_to\_da\_moon** ” 和 “ **cc draw 1 BTC 100 \#BTC\_to\_da\_moon** ” 带口令空投举例。

你需要在频道里回复 “ **\#BTC\_to\_da\_moon** ” ，将能领取币。

## 打赏

如果你想给在频道中积极发言，贡献过很多好主意的人打赏代币，鼓励他们分享更多有价值的信息，使用打赏指令。

在 Discord上打赏仅需 2 步：

1. 充值  
向你的账户充值足够的币。

2. 打赏  
在频道中加入 @CCTip Bot\#0897 ，并输入打赏指令。打赏一个或多个人

以 “**cc 0.01 ETH @peter @lucy @mary**” 为例，在频道中发送该指令会进行一次打赏。

该打赏的规则是：CCTip Bot 被拉进频道后，peter、lucy、mary 将每人获得 0.01 ETH。

指令格式：

> cc TokenAmount TokenSymbol @user1 @user2 @userN

## 群设置

通过群设置，管理员能设置仅限管理员发红包，指定本群打赏或空投的币种，设置本群文字广告。

### **修改群设置入口**

#### 入口一：频道中回复**“cc serverset”进入群设置页面**

如果你是管理员，你可以在频道内回复“**cc serverset**”，CCTip Bot 将会私信你一条消息。点击链接打开网页进行设置，点击“确定”按钮后群设置将立即生效。

![](../.gitbook/assets/image%20%28213%29.png)

#### 入口二：点击[这里](https://my.cctip.io/discord/group/settings)进入页面进行设置

![](../.gitbook/assets/image%20%28209%29.png)

### 修改方法

#### 指定本服务器打赏或空投的币种

通过设置服务器内币种白名单，限制服务器内支持代币种类，避免被支持其他代币种类的用户影响群内交流气氛。

_注意：白名单仅允许设置已购买 CCTip 中 Discord 服务的币种。_

设置方法：  
打开“仅允许以下代币打赏和空投”的开关，选择你想设置的币种即可。

![](../.gitbook/assets/image%20%28320%29.png)

#### 仅允许机器人在指定频道中发言

若你担心机器人在各频道消息过多，影响频道内的讨论氛围，可以设置机器人仅能在某些频道中发言。

设置方法：   
打开“仅允许机器人在以下频道中发言”的开关，并选择对应的频道即可。

![](../.gitbook/assets/image%20%28164%29.png)

**仅允许指定身份组成员在频道内空投**

通过设置此项，限制可以发空投的身份组成员，避免频道内空投过多，影响频道内的讨论氛围。

设置方法：  
打开“仅允许以下身份组成员在频道内空投”的开关，并选择对应的身份组即可。

![](../.gitbook/assets/image%20%28183%29.png)

**设置服务器内允许的空投类型**

空投类型包括 Airdrop, Draw 和 Rain，你可以根据服务器的需要，仅允许某几种空投类型。

设置方法：  
选择允许的空投类型即可。

![](../.gitbook/assets/image%20%28292%29.png)

**设置用户领取空投的方式**

领取空投有两种方式可选择，点击 emoji 领取和在群内回复对应的口令领取。

两者各有优势：

* 点击 emoji 领取既可以活跃频道内成员，又不会造成频道内刷屏
* 在群内回复对应的口令领取，可以激活频道内长期沉默不发言的用户，激励他重新参与频道内讨论。

设置方法： 

在“设置用户领取空投的方式”中，选择对应的领取方式即可。

![](../.gitbook/assets/image%20%28235%29.png)

#### 设置服务器内广告

设置服务器内文字广告后，空投创建及空投领取结束时，CCTip Bot 回复的消息中将附带广告内容。

设置方法：  
打开“广告“的开关，输入你想设置的广告内容即可。

![](../.gitbook/assets/image%20%2849%29.png)

### 查看群设置

若你想查看当前频道的设置，在群内发送指令 "**cc viewserverset**" 查看。

指令格式：

> cc viewserverset

## 查询币种价格

私信 CCTip Bot 发送指令 “**price BTC**”，机器人将返回 BTC 实时价格。查询其他代币价格，只需将 BTC 换成其他代币符号即可。

指令格式：

> price 币种符号

## 查询支持的币种

私信 CCTip Bot 发送指令 “**coins**” ，机器人将返回目前 CCTip 已支持的空投代币。  
如果你想打赏或空投的代币不在列表中，[联系我们添加](https://my.cctip.io/token/listing)

## [资金划转](https://doc.cctip.io/guide-cn#zi-jin-hua-zhuan)

## [CCTip·兑换](https://doc.cctip.io/guide-cn#cctip-dui-huan)

