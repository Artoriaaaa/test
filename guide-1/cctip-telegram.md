# CCTip @Telegram

## 充值

#### 方式一：私信机器人充值

以充值 ETH 为例，向 cctip\_bot 发送私信指令“**deposit ETH**”，机器人将返回你的专属 ETH 充值地址。使用你的钱包向该地址转账 ETH，达到一定的确认数之后，CCTip 将为你入账。充值其他币种，请将指令中的 “**ETH**” 换成其他币种符号。

#### 方式二：在 My CCTip 中充值

以充值 ETH 为例。

用自己的 Telegram 账号登录 [my.cctip.io](https://my.cctip.io/), 进入“**Balance-&gt;BTC**”页面，点击“**Deposit**”。使用你的钱包向你的专属 ETH 充值地址转账 ETH，达到一定的确认数之后，CCTip 将为你入账。充值其他币种，请点击对应代币的“**Deposit**”。

**不同币种入账所需的条件如下：**

* ETH & ERC20 : 12 个确认数 
* BCH & SLP ： 2 个确认数
* BTC ： 2 个确认数   
* TRX：状态为已确认
* DOGE:  10 个确认数
* LTC ： 5 个确认数
* BSV ： 2 个确认数
* DASH ： 6 个确认数
* ZIL ： 6 个确认数

## 查询余额

向 cctip\_bot 发送私信指令 “**balance**”，机器人将返回你所有的余额不为 0 的代币余额。

## 提现

#### 方式一：私信机器人提现

以将 1.01 个 BTC 提现到 17Ui3e2cnwb13cdWxASBHsC6qZ56YKj3gj 为例。  
向 cctip\_bot 发送私信指令 “**withdraw 1.01 BTC 17Ui3e2cnwb13cdWxASBHsC6qZ56YKj3gj**” ，如果你的余额足够，CCTip 将处理你的提现请求，并在 10 分钟内汇出。

提现时，请根据你的提现需求替换指令中的数量，币种，地址等信息。

#### 方式二：在 My CCTip 中提现

以将 1.01 个 BTC 提现到 17Ui3e2cnwb13cdWxASBHsC6qZ56YKj3gj 为例。

用自己的 Telegram 账号登录 [my.cctip.io](https://my.cctip.io/), 进入“**Balance-&gt;BTC**”页面，点击“**Withdraw**”，输入提现金额 1.01, 在提现地址输入 17Ui3e2cnwb13cdWxASBHsC6qZ56YKj3gj，完成验证后，CCTip 将处理你的提现请求，并在 10 分钟内汇出。

**不同币种所需的提现费用不同，如下：**

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

## 创建空投

创建空投即可以将你喜爱的代币发送给更多的人，也可以增加群组的活跃度。

在 Telegram 群组中创建空投仅需 2 步：

1. 充值  
向你的账户充值足够的币

2. 拉 cctip\_bot 进群  
在群中加入 cctip\_bot，并输入创建空投指令。

#### 1.创建一个金额随机空投

如果你希望每个人领取到的金额不同，可以创建一个随机空投。  
以 “cc airdrop 1 BTC 100” 为例，在群组中发送该指令会创建了一个金额随机空投。  
该空投的规则是：接下来在群内发送 “**grab**” 的前 100 人，将会共同瓜分 1 BTC，每人获得的金额随机。

指令格式：

> cc draw TokenAmount TokenSymbol NumberOfPeople  
> cc airdrop TokenAmount TokenSymbol NumberOfPeople

#### 2.创建一个带口令的金额随机空投

如果你希望每个人领取到的金额不同，并且发言内容必须包含某个关键词才能领取空投，可以创建一个带口令的金额随机空投。

以 “**cc airdrop 1 BTC 100 \#BTC\_to\_da\_moon**” 为例，在群组中发送该指令会创建一个带口令的金额随机空投。

该空投的规则是：接下来在群里发送 “**\#BTC\_to\_da\_moon**” 的前 100 人，将会共同瓜分 1 BTC，每人获得的金额随机。

指令格式：

> cc draw TokenAmount TokenSymbol NumberOfPeople \#keywords  
> cc airdrop TokenAmount TokenSymbol NumberOfPeople \#keywords

#### 3.创建一个giveaway

如果你想在群里发空投，并且不希望群里被领取空投的消息刷屏，你可以使用 giveaway 指令。

以 “**cc** **giveaway 1 BTC 100**” 为例，在群组中发送该指令会创建一个金额随机空投。该空投的规则是：接下来在群内点击 “立即瓜分 1 BTC” 按钮的前 100 个用户，将会共同瓜分 1 BTC，每人获得的金额随机。

指令格式：

> cc giveaway TokenAmount TokenSymbol NumberOfPeople

## 领取空投

#### 领取普通的空投

普通的空投不带口令，例：“**cc airdrop 1 BTC 100**” 和 “**cc draw 1 BTC 100**”。

你只需在群里发送 “**grab**” 后，将能领取币。

#### 领取带口令的空投

以 “**cc airdrop 1 BTC 100 \#BTC\_to\_da\_moon**” 和 “**cc draw 1 BTC 100 \#BTC\_to\_da\_moon**” 带口令空投举例。

你需要在群里回复 “**\#BTC\_to\_da\_moon**” ，将能领取币。

## 红包雨

如果你想随机给群内的用户发红包，炸出更多潜水用户，鼓励他们更加积极活跃参与讨论，可以使用红包雨指令。

以 “cc rain 1 BTC 100” 为例，在群组中发送该指令会开始挥洒红包雨。

该红包雨的规则是：随机给群内 100 个幸运儿发红包，每人获得 0.01 BTC。

指令格式：

> cc rain 代币数量 代币符号 红包雨人数

## 打赏

如果你想给在群中积极发言，贡献过很多好主意的人打赏代币，鼓励他们分享更多有价值的信息，使用打赏指令。

在 Telegram 群组中打赏仅需 2 步：

1. 充值  
你的账户充值足够的空投币。

2. 拉 cctip\_bot 进群  
在群中加入 cctip\_bot，并输入打赏指令。

#### 1.打赏一个人

以 “**cc 0.01 ETH @lisa**” 为例，在群组中发送该指令会进行一次打赏。

该打赏的规则是：cctip\_bot 被拉进 Telegram 群后，只要 lisa 在群里曾经发过消息，lisa 将获得 0.01 ETH。

指令格式：

> cc 代币数量 代币符号 @user

#### 2.打赏多个人

以 “**cc 0.01 ETH @peter @lucy @mary**” 为例，在群组中发送该指令会进行一次打赏。

该打赏的规则是：cctip\_bot 被拉进 Telegram 群后，只要 peter、lucy、mary 在群里曾经发过消息，他们将每人获得 0.01 ETH。

指令格式：

> cc 代币数量 代币符号 @user1 @user2 @userN

#### 3.带备注内容的打赏

如果你想在打赏中添加备注内容，可以在指令中增加备注内容，例：“**cc 0.01 ETH @peter @lucy @mary \#感谢关注**”

指令格式：

> cc 代币数量 代币符号 @用户1 @用户2 @用户N \#备注内容

## 快捷指令

指令输入过于复杂？容易输错？没关系，CCTip 为你提供快捷指令。通过快捷指令，你可以输入更少的文字或使用更个性化的文字来发起空投，进行打赏。快捷指令分为免费的快捷指令和专属快捷指令，免费快捷指令你可以直接在有 cctip\_bot 群聊中使用，专属快捷指令则需要购买后才能生效。

#### 1. 免费的快捷指令

下列快捷指令可免费使用：

**cc drawbch**：该指令等同于指令 “**cc draw 0.001 BCH 10**”，即在群内发送 “**grab**” 的前 10 个人将会立即参与瓜分 0.001 BCH，每人获得的金额随机。

**cc draweth**：该指令等同于指令 “**cc draw 0.001 ETH 10**”，即在群内发送 “**grab**” 的前 10 个人将会立即参与瓜分 0.001 ETH，每人获得的金额随机。

**cc drawbtc**：该指令等同于指令 “**cc draw 0.00005 BTC 10**”，即在群内发送 “**grab**” 的前 10 个人将会立即参与瓜分 0.00005 BTC，每人获得的金额随机。

**cc drawusdt**：该指令等同于指令 “**cc draw 0.2 USDT 10**”，即在群内发送 “**grab**” 的前 10 个人将会立即参与瓜分 0.2 USDT，每人获得的金额随机。

**cc drawspice**：该指令等同于指令 “**cc draw 100 SPICE 10**”，即在群内发送 “**grab**” 的前 10 个人将会立即参与瓜分 100 SPICE，每人获得的金额随机。

#### 2. 购买专属快捷指令

专属指令 1.99 USDT/30天，最少购买30天，最多180天。购买成功将扣除账户中的 USDT。

1.购买方法：

以购买 “**cc GetRichTegother**” 快捷指令 30 天，并设置为每次发总金额为 1.2 ETH，数量为 10 的金额随机空投为例。   

向 cctip\_bot 发送私聊指令 “**buyWords GetRichTegother = 30 airdrop 1.2 ETH 10**”，cctip\_bot 会自动检测你的账户余额，若余额足够将会自动扣除相应费用并告知购买成功。   

2.使用方法：

购买成功后，30天内，你可以直接在有 cctip\_bot 的群内使用。   

创建普通空投：发送指令 “**cc GetRichTegother**”，即接下来在群内发送 “**grab**” 的前 10 个人将会立即参与瓜分 1.2 ETH，每人获得的金额随机。   

创建带口令的空投：以口令 “**123**” 为例发送 “**cc GetRichTegother \#123**”，即接下来在群内发送 “**\#123**” 消息的前 10 个人将会立即参与瓜分 1.2 ETH，每人获得的金额随机。   

指令格式：

> buyWords 快捷指令名称 = 购买天数 详细指令

## 拉群奖励

邀请 @cctip\_bot 到更多的 Telegram 群获得代币奖励。操作 3 步，坐收空投：

1. 将 cctip\_bot 拉进 Telegram 群  
2. 在群内空投并教会群内成员使用 CCTip  
3. 接下来的 30 天，你将自动领取该群中每个数量超过 10 的空投作为奖励

注意：每个群的群邀请人为第一个邀请 cctip\_bot 进群的人，重复邀请无效。  
群内空投越多、越频繁，意味着你将获得更多奖励，不要犹豫，开始使用 CCTip 赚取更多代币吧！

#### 查看拉群奖励

私聊 cctip\_bot 回复指令 “**view\_my\_promo\_rewards**”，即可查看最近 10 条邀请奖励及获得的累计奖励。

指令格式：

> view\_my\_promo\_rewards

## 群设置

通过群设置，管理员可以设置新人奖励，指定仅允许管理员发红包，指定本群打赏或空投的币种，设置本群文字广告。

### **修改群设置入口**

#### 入口一：群聊中回复“/group\_setting@cctip\_bot“进入群设置页面

如果你是群管理员，你可以在群内回复“**/group\_setting@cctip\_bot**“进入群设置页面，并在修改完各个设置后，点击底部的按钮“设置“，所有设置将立即生效。CCTip 会在群内告诉你设置成功。

![](../.gitbook/assets/image%20%2875%29.png)

#### 入口二：点击[这里](https://my.cctip.io/telegram/group/settings?manager=0)进入页面进行设置

![](../.gitbook/assets/image%20%2843%29.png)

### 修改方法

如果你是在群聊中回复“/group\_setting@cctip\_bot“进入群设置页面，在修改完各个设置后，点击底部的按钮“设置“，所有设置将立即生效。CCTip 会在群里告诉你设置成功。

![](../.gitbook/assets/image%20%28116%29.png)

如果你是通过其他方式进入的群设置页面，在修改完各个设置后，点击底部的按钮“设置“，CCTip 将为你生成一个指令。复制该指令，并发送至你管理的群聊中，所有设置将立即生效。

#### **各群设置项介绍及修改方法**

#### 升级为 DAO 群

DAO 群是指满足一定条件的用户加入的群。通过设置DAO 群，你可以有效管理群，要求群成员必须在链上或 CCTip 账户中至少持有一定数量的某种代币才能加入该群。

设置方法：   
打开“**升级为DAO 群**”的开关，选择链，输入代币合约地址，输入最小持币数量即可。如果你希望设置该链的 coin，直接点击下拉选择即可。

以设置“群内成员必在 ETH 链上持有 ≥ 0.0001 USDT”为例，设置方法如下：

选择 ETH，输入 USDT 合约地址，输入 0.0001 即可。

**注意：  
1.升级为DAO 群前，请将 @cctip\_bot 设置为 admin，并为其添加 ”ban users“ 权限。否则机器人将无法踢出群成员**

#### 设置新人奖励

通过设置新人奖励，你可以鼓励群内成员邀请新成员进群。当有新人加入群时，邀请人和被邀请人都将获得奖励。

设置方法：  
****打开“新人奖励”的开关，选择奖励代币、输入邀请者获得的奖励数量、新人获得的奖励数量即可。如果你担心新人奖励被刷，你可以设置领取口令来避免假账号领取新人奖励。

以设置邀请人奖励 0.4 BCH、被邀请人奖励 0.6 BCH，领取条件为回复口令“Hi, everybody”为例，设置方法如下：

![](../.gitbook/assets/image%20%28281%29.png)

如果在“领取口令“一栏为空，新人入群即可获得奖励。

_注意：只有通过群右上角 “···” - “Add member” 邀请新人入群才能获得邀请人奖励。_

![](../.gitbook/assets/image%20%28252%29.png)

#### 指定仅允许群主或管理员进行空投

你可以通过群设置，设置群内只有群主和管理员可以进行空投。

设置方法：  
打开“指定仅允许群主或管理员进行空投”的开关即可。

![](../.gitbook/assets/image%20%2867%29.png)

#### 指定仅允许群主或管理员进行打赏

你可以通过群设置，设置群内只有群主和管理员可以进行打赏。

设置方法：  
打开“指定仅允许群主或管理员进行打赏”的开关即可。

![](../.gitbook/assets/image%20%28302%29.png)

#### 指定群内允许使用的空投类型

群内默认 Airdrop、draw、giveaway 均可使用。如果你担心群成员抢红包造成刷屏，可以设置成仅允许在群内使用 giveaway。设置后，空投活跃群内气氛的同时，群内又不会被抢红包口令刷屏。

设置方法：  
勾选允许使用的空投类型即可。

![](../.gitbook/assets/image%20%28166%29.png)

#### 指定本群打赏或空投的币种

通过设置群内币种白名单，限制群内支持代币种类，避免被支持其他代币种类的用户影响群内交流气氛。

_注意：白名单仅允许设置已购买 CCTip  中 Telegram 服务的币种。_

设置方法：  
打开“仅允许以下代币打赏和空投”的开关，选择你想设置的币种即可。

![](../.gitbook/assets/image%20%28320%29.png)

#### 设置群内广告

设置群内文字广告后，空投创建及空投领取结束时，cctip\_bot 回复的消息中将附带广告内容。

设置方法：  
打开“广告“的开关，输入你想设置的广告内容即可。

![](../.gitbook/assets/image%20%2849%29.png)

### 查看群设置

若你想查看当前所在群的设置，在群内发送指令  “**/group\_setting@cctip\_bo**t” 或 "**cc viewgroupset**" 查看。

指令格式：

> /group\_setting@cctip\_bot  
> cc viewgroupset

## **链上地址**

绑定链上地址后可以加入持币群。

### 如何绑定链上地址？

以使用 MetaMask 绑定 ETH 地址为例。你需要先在 Chrome 中安装 [MetaMask 插件](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn)，并导入/创建你的钱包。

在 [my.cctip.io](../guide/faq/i-cant-log-in-to-my.cctip.io.-what-should-i-do.md) 中找到“链上地址”，选择要绑定点链，点击“绑定”，选择一个钱包，完成签名即可。

### 如何修改链上地址？

如果你已绑定了一个链上地址，需要修改绑定的地址，你需要现在插件中切换账户地址。以 MetaMask 为例。找到 MetaMask 插件，点击右上角”账户“进行切换，切换至要修改的地址账户。切换后，在网页中，点击“修改”，选择 MetaMask，重新进行签名，修改成功！

## 查询币种价格

向 cctip\_bot 发送私信指令 “**price BTC**”，机器人将返回 BTC 实时价格。查询其他代币价格，只需将 BTC 换成其他代币符号即可。

指令格式：

> price 币种符号

## 查询支持的币种

向 cctip\_bot 发送私信指令 “**coins**” ，机器人将返回目前 CCTip 已支持的空投代币。  
如果你想空投的代币不在列表中，[联系我们上币](https://my.cctip.io/token/listing)

## [资金划转](https://doc.cctip.io/guide-cn#zi-jin-hua-zhuan)

## [CCTip·兑换](https://doc.cctip.io/guide-cn#cctip-dui-huan)

