# 文案助手项目

**一句话价值主张：让校对变得更简单。**

#### 基本信息

|项目名称|文案助手|
|---|---|
|更新时间|2019/12/8|
|项目负责人|SHIRKING|
|项目状态|起草中|
|第一更新地|[gitee链接](https://gitee.com/NFUNM045/CopywritingAssistant)|


#### 项目简介（60秒价值主张）

不难发现，各个平台上活跃着大量的内容生产者。他们可能是融媒体编辑，可能是网络文学创作者。他们之间的文学水平参差不齐，对于很多个人创作者而言内容中出现错误很可能发生。这些错误虽然可以通过各种方式进行后期修改更正，但是难免会对消费者产生影响，并且会消耗更大的时间成本。为此，我们团队设计了一款文案助手的APP，利用百度AI中文本纠错等API为内容创作者减负，通过识别文本中的错误片段并给出错误提示与建议，做到从源头减少文本中的常见性错误。

[20×20价值主张](https://gitee.com/NFUNM045/CopywritingAssistant/blob/master/%E6%96%87%E6%A1%88%E5%8A%A9%E6%89%8B.pptx)


## 一、市场定位及发展方向

我们的市场定位是一个为内容创作者而专设的助手类产品。通过市场调查及项目初步评估我们团队认为，文案助手这一项目有不小的发展前景。现如今内容创作者浩如烟海，我们生活在一个快节奏的时代，内容创作也是赶着时间的。传统的编辑审稿花费的时间不少，我们项目就是看准这一点，为创作者及编辑减负，缩短内容创作者与编辑审稿的时间，让他们的时间更加专注于内容本身，而不是一些简单的文字错误。

由于政府对于文化事业的重视，文化产业的发展前景是明朗而乐观的。社会上内容创作者的数量是肉眼可见地在不断攀升，或者说人人都是内容创作者，但是编辑与内容创作者是不成比例的。我们项目地主要客户及潜在客户是巨量的，我们面对的市场也是巨大的。加之如今的机器学习技术不断发展，我们可以获取到的技术与资源包也在不断地丰富，我们项目实现落地的机率极高。未来发展也是一片向好的。

我们APP的初步计划是制作一个简单轻便的内容创作插件，用于识别文案中的错别字，辅助用户写作。之后，随着用户活跃度提高，再推出更多文案写作相关功能丰富APP本身，添加在线写作、机器审核、语音输入、OCR识别、内容收藏、热点推荐等等功能。最后创建一个内容创作者的专业助手，尽可能解决其文案写作中遇到的各种问题，缩短创作过程中可能浪费的时间，让内容创作者抒发灵感的道路上更加顺畅。

## 二、加值宣言

本项目通过使用文本纠错、文本审核、手写文字识别等API辅助内容创作者写作。通过识别文本中有错误的片段，进行错误提示并给出正确的建议文本内容，检测文本中夹杂的垃圾内容，识别内容创作者手写的大篇幅文字等功能让内容创作者能够更加高效快捷的完成创作。


## 三、核心价值

本产品的核心交互是通过使用文本识别API识别用户提交文本中的错别字，并给出修改意见，辅助用户完成文案写作。

产品的核心价值在于缩短内容创作者在创作过程中可能浪费的时间，为其及其编辑省去反复多次为了错别字而做的核查与校对，也让内容创作者抒发灵感的道路上更加顺畅。

## 四、痛点（核心价值与用户痛点）

我们在对内容创作者的观察中发现，内容创作者尤其是个人内容创作者很可能因为错别字造成各种各样的人力物力上的损失同时影响其内容消费者的印象。

### 痛点场景及预测

1.客户在内容创作时由于错别字的出现，要返回去修改内容，错别字的出现打断了创作者的思考。

2.客户由于疏忽将含有错别字的内容推送给了他的消费者，客户自己发现了，文章需要修改再次编辑。

3.客户由于疏忽将含有错别字的内容推送给了他的消费者，之后被其消费者指出，使其消费者对内容创作者的印象扣分。

第2、3个场景中不仅是浪费创作者的时间，而且不同的平台可能消耗的成本是不同的。如果是新浪等有修改功能的平台还可以通过编辑更正，一些没有编辑功能的平台或方式则需要通过其他方式解决。

### 人工智能概率性与用户痛点

本产品主要用于文案辅助，对用户进行提醒，给用户一个参考，最后的抉择依旧由用户自己做出，保持了用户的自由选择度。


## 五、客户细分

内容创作者（尤其是个人创作者，即没有编辑辅助的创作者）

### 需求列表与人工智能API加值

|需求列表|人工智能API|优先级|
|---|---|---|
|省去检查错字带来的时间浪费|文本纠错API|最高|
|快速审核文章是否符合要求|文本审核API|较高|
|能够在线写作||较高|
|将手写的文案内容变成文字|手写文字识别API|一般|
|语音输入文字|语音识别|一般|
|对文章进行分类|文章分类API|较低|
|……|……|……|


## 六、原型

### 6.1 交互与界面设计·低保真原型：

**交互的过程中能够通过一键点击调取数据。**

**1.展示页**

1.1 点击“主页”与“设置”可以切换页面。

1.2 点击“错字识别”可以进入错字识别编辑页。

1.3 在主页也能够编辑管理相关文件，并调用其他功能。

1.4 在设置页能够对悬浮窗进行设置，调整其颜色及功能加减。

1.5 在这两个页面都可以点击下方圆形按钮一键开关悬浮窗。


![主页](https://images.gitee.com/uploads/images/2019/1223/140733_363be363_1648188.png "微信图片_20191223140622.png")
![设置](https://images.gitee.com/uploads/images/2019/1223/140746_7d13627e_1648188.png "微信图片_20191223140636.png")

**2.1 功能页**

2.1.1 悬浮窗用作快速调用功能的一个方法。

2.1.2 点击“错字识别”可以进入错字识别编辑页。

2.1.3 点击其他功能键进入其他功能页。

![浮窗](https://images.gitee.com/uploads/images/2019/1223/140758_3b5644d1_1648188.png "微信图片_20191223140639.png")

**2.2 智能功能页**

2.2.1 编辑页能够使用API功能。

2.2.2 点击“错字识别”，APP将调取API对文本框内的文本进行分析，查找出有误的字体。

![编辑](https://images.gitee.com/uploads/images/2019/1223/140812_7bb480f4_1648188.png "微信图片_20191223140642.png")
![点击后](https://images.gitee.com/uploads/images/2020/0101/182938_ad9bddab_1648188.png "微信图片_20200101182552.png")

### 6.2 信息设计：

**在编辑中会以图形界面改变的形式反馈出API检测后的结果。**

### 6.3 原型文档：

**产品架构**
![产品架构](https://images.gitee.com/uploads/images/2019/1224/144657_0774c375_1648188.png "文案助手产品架构.png")

[原型文档链接](https://nfunm045.gitee.io/api_prototype_warehouse)

### 6.4 口头操作说明：

该产品主要有以下四个界面：主页、设置、浮窗、编辑。
操作简单易懂，进入APP可以开启浮窗快速进入编辑页。主页主要用作调取文档、进入页面。设置则是对浮窗功能的设置。编辑就是用户的主要工作台，处理所有文档内容。另外：手写识别将调取用户的摄像头，最终成果也会展示在编辑页面。


## 七、API产品使用关键AI或机器学习之API的输出入展示

在原型中，功能页（编辑页）呈现其API输出效果

### 1.使用水平


**示例代码如下：**


```python
def txt_correction(content):
    print ('原文：',content)
    token=get_token()
    url = 'https://aip.baidubce.com/rpc/2.0/nlp/v1/ecnet'
    params = dict()
    params['text'] = content
    params = json.dumps(params).encode('utf-8')
    access_token = token
    url = url + "?access_token=" + access_token
    request = urllib.request.Request(url=url, data=params)
    request.add_header('Content-Type', 'application/json')
    response = urllib.request.urlopen(request)
    content = response.read()
    if content:
        content=content.decode('GB2312')
        data = json.loads(content)

        item=data['item']
        print('纠错后：',item['correct_query'])
        print('Score：',item['score'])
        
txt_correction('一场篮球赛后，我们都汗流夹背。')
```
**本地运行效果：**
![汗流浃背代码](https://images.gitee.com/uploads/images/2019/1227/150229_c4f2728f_1648188.png "汗流浃背代码.png")

![后台反馈内容](https://images.gitee.com/uploads/images/2019/1211/002654_9ac0616d_1648188.png "微信图片_20191210201608.png")

**图形界面测试：**

![反馈](https://images.gitee.com/uploads/images/2019/1211/002821_c34c8b8e_1648188.png "微信图片_20191210201517.png")

其他简单测试：

|测试|反馈|结果|后台|
|---|---|---|---|
|生机勃勃|![生机勃勃](https://images.gitee.com/uploads/images/2019/1211/002500_ad13fc1d_1648188.png "微信图片_20191210201550.png")|正确|![生气](https://images.gitee.com/uploads/images/2019/1227/151939_e26a3daa_1648188.png "生气.png")|
|顽皮白鲸|![顽皮白鲸](https://images.gitee.com/uploads/images/2019/1211/002616_55d6c352_1648188.png "微信图片_20191210201554.png")|正确|![白鲸后台](https://images.gitee.com/uploads/images/2019/1227/151732_2c955e66_1648188.png "白鲸.png")|



### 2.使用比较分析

|API平台|结果简析|相关信息截图|
|---|---|---|
|微软|在微软的文本分析API中我们还没有能够找到关于纠错改正等开放API。我个人看法是因为微软所面向的群体较广，还未能够有一个专门面对汉语处理的功能。|![微软文本分析API](https://images.gitee.com/uploads/images/2019/1208/143449_d1d42604_1648188.png "微软api.png")|
|百度|百度API中自然语言处理中有具体的文本纠错模块。由于是中国公司，对汉语的针对性比较强。对比其他家自然语言处理技术，百度发展得更快。|![百度文本纠错API](https://images.gitee.com/uploads/images/2019/1210/191953_7e27b8bf_1648188.png "百度.png")|
|阿里云|阿里同样作为中国公司，其着重点更在于线上交易相关内容，对于自然语言处理优先度不算特别高。与微软相同，阿里还没有文本纠错相关的开放API。|![阿里云API](https://images.gitee.com/uploads/images/2019/1210/192452_f30b16f7_1648188.png "阿里云API.png")|





### 3.使用后风险报告

1.文本纠错API产品定价
项目制作中需要一定的制作经费预算。

![产品定价](https://images.gitee.com/uploads/images/2019/1211/004750_efeda132_1648188.png "产品定价.png")

2.核心API文本纠错API的单次输入限制为511字节，支持并发。这一定程度上对我们的产品设计有影响。

3.由于要实现同样功能并不算难，文案助手有许多潜在的竞争对手，包括一些原本就有大量用户基础的写作软件以及输入法软件。

4.文案助手是以助手形式存在的。对于主观性较强的文本纠错、内容审核，很难完全做到纠错与审查。在这方面的准确度仍然有提升的空间，技术上的提升还是需要一定时间的。

5.手写识别需要用到用户的摄像头权限，可能会劝退用户。




相关资料链接：
[百度token获取方法](https://ai.baidu.com/ai-doc/REFERENCE/Ck3dwjhhu)

[文本纠错API教程](https://ai.baidu.com/forum/topic/show/942913)

[百度文本纠错API简单介绍](https://ai.baidu.com/tech/nlp_apply/text_corrector)

[百度文本纠错技术文档](https://ai.baidu.com/ai-doc/NLP/Yk3h7h9o5#%E6%96%87%E6%9C%AC%E7%BA%A0%E9%94%99%E6%8E%A5%E5%8F%A3)
