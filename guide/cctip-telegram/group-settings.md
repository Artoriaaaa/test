# Group Settings

Through the [group setting](https://my.cctip.io/telegram/group/settings), the admins can set the admins as the only people who can send airdrops, specify the cryptocurrency for tips or airdrops in this group, and set the text ad in the group.

## **Modify the entrance to the group settings**

#### Entrance 1: Reply with "**/group\_setting@cctip\_bot**" in group chat to enter the page of group settings

Reply with "**/group\_setting@cctip\_bot**" in the group chat you manage, click the button in the robot reply to enter the page of group settings.

![](../../.gitbook/assets/image%20%28205%29.png)

#### Entrance 2: Click [here](https://my.cctip.io/telegram/group/settings?manager=0) for settings

![](../../.gitbook/assets/image%20%28290%29.png)

### Modification method

If you reply with "**/group\_setting@cctip\_bot**" in the group chat to enter the page of group settings, you can click the button "Confirm" at the bottom after modifying all items, and all the settings will take effect immediately. CCTip will inform you of successful settings in the group.

![](../../.gitbook/assets/image%20%28142%29.png)

If you enter the page of group settings by other means, after modifying each item, click the button "Confirm" at the bottom, and CCTip will generate a command for you. Copy the command and send it to the group chat you manage, and all settings will take effect immediately.



## **Information and modification method of each item of group settings**

### 🔥 Upgrade to DAO Group

The DAO Group refers to a group of users who meet certain conditions. You can easily set a threshold to allow in only those who hold at least a certain amount of certain tokens on the chain or in a CCTip account.

Setting method:   
Switch on **"Upgrade to DAO Group"**, select the chain, enter the token contract address, and enter the minimum number of holdings. If you want to set the coin of the chain, just click the pull-down menu to select one.

**Rule of DAO group: CCTip will verify the qualification when users join or speak, and will remove those disqualified.**

Take the setting of “**group members must hold ≥ 0.0001 USDT on the Ethereum** ” as an example. The setting method is as follows:  
Select ETH, enter the USDT contract address, and enter 0.0001. __Remember to add "**Ban User"** permission for **@cctip\_bot,** otherwise the bot can not remove those disqualified.

![](../../.gitbook/assets/image%20%28103%29.png)

![](../../.gitbook/assets/image%20%28195%29.png)

![](../../.gitbook/assets/image%20%28105%29.png)

### Set newcomer rewards

By setting newcomer rewards, you can encourage members to invite new users to the group. In a group with newcomer rewards, both the inviter and the newcomer will be rewarded. 

Setting method:  
Activate the option "Newcomer rewards", select the reward token, enter the amount of rewards received by the inviter and by the newcomer. To avoid cheating, you can set a keyword to prevent fake accounts from receiving the newcomer rewards.

For example, if the inviter rewards are 0.4 BCH and the newcomer rewards 0.6 BCH and the newcomer needs to reply with the keyword "\#Hi, everybody" before getting rewards, you need to set as below:

![](../../.gitbook/assets/image%20%28316%29.png)

If the "Keyword for receipt" field is empty, the newcomer can get the rewards as soon as they join the group.

_Note: Only by clicking "···" - "Add member"  in the upper right corner of the group and inviting newcomers can you receive the inviter rewards._

![](../../.gitbook/assets/image%20%2847%29.png)

### Set the admins as the only people who can send airdrops

If you want to set the admins as the only people who can send airdrops,  you need to set as below.

Setting method:  
Just activate the option that "Only the admins can send airdrops".

![](../../.gitbook/assets/image%20%28231%29.png)

### Set the admins as the only people who can tip

If you want to set the admins as the only people who can tip,  you need to set as below.

Setting method:  
Just activate the option that "Only the admins can tip".

![](../../.gitbook/assets/image%20%287%29.png)

### Set the type of airdrops allowed in the group

Airdrop, draw, and giveaway are all allowed in the group by default. For concerns over messages flooding the screen from members grabbing airdrops, you can set giveaway as the only type allowed in the group so that the airdrop will activate the atmosphere in the group with no keywords flooding the screen.

Setting method:  
****Check the type of airdrops allowed.

![](../../.gitbook/assets/image%20%28166%29.png)

### Set the supported cryptocurrencies in the group

By setting a whitelist of cryptocurrencies, you can restrict the types of coins/tokens supported in the group to prevent users who support other types of coins/tokens from affecting the internal communication atmosphere.

Setting method:  
Activate the option that "Only the following tokens are allowed to be tipped and airdropped" and then select the coin/token you want to set.

For example, to set BTC and ETH as the only supported cryptocurrency in the group, follow the steps as below:

![](../../.gitbook/assets/image%20%28178%29.png)

_Note: In the whitelist of cryptocurrencies, only coins/tokens that have purchased the Telegram service in CCTip can be set._

### Set the ad in the group

After the text ad in the group is set, cctip\_bot will reply messages containing the ad after an airdrop is created and when the airdrop is end.

Setting method:  
Activate the option "Ad", and enter the content of your advertisements you want to set.

For example, to set “**CCTip-the best tipping tool**” as the ad in the group, follow the steps as below:

![](../../.gitbook/assets/image%20%28308%29.png)

## View group settings

If you want to view the group settings currently set in the group, reply "**/group\_setting@cctip\_bot**" or "**cc viewgroupset**".

Command format:

> /group\_setting@cctip\_bot  
> cc viewgroupset

