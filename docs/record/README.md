# 记账界面
此界面是微微记账的核心界面，账单的添加和修改都在此界面完成。记账界面主要包括以下几个模块：
### 1. 分类列表
展示所有支出/收入下面的分类，每一笔账单，都必须选择一个分类，默认会选择第一个分类。 \
如果分类比较多，可以上下滚动，所有分类都可以在此选择。

另外，点击分类列表最后一项，可以进入分类管理页面。

### 2. 选择账户
点击账户项，可以选择资金账户，默认只有**不计入账户**一项。 记账时选择对应的消费账户，则会自动扣除该账户中的金钱。\
怎样添加资金账户，可以前往[资产管理](/assets/)查看。

### 3. 备注
备注是用来对单个账单进行详情说明的，能够让账单更加详细，备注内容是可选的，可以根据自己需要填写。\
备注内容一般都说明该笔账单的详细用途，不建议写太长，否则客户端可能展示不全。

### 4. 时间
代表该笔账单消费的具体时间，点击该按钮，则会弹出日期选择对话框。
进入记账界面后，时间默认选择**今天**。
> Tips \
> 如果开启了【设置】页面的账单时间功能，在日期选择弹窗，还可以选择消费的具体时间 \
> 上面滑动时间按钮，则可以切换记账日期，向上滑动，日期+1，向下滑动，日期-1

### 5. 报销
当记账时，如果勾选了**报销选项**，则该笔账单会标记为一笔报销账，可以在**报销管理**界面统一处理报销业务。

### 6. 计算器面板
计算器面板用于记账时输入，输入消费金额，以小数来显示，最多可以输入两位小数。\
目前计算器里面支持的四则运算只有加法，减法。

- **删除**，点击将会删除单个字符，长按会清除所有输入。
- **完成**，点击后，会将选择的分类、时间、备注、金额、生成一笔新的账单保存，然后关闭当前记账界面。
- **再记**，”再记一笔“的简写，是为了方便连续记账。