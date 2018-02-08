# macbook_issues
《macOS软件安全与逆向分析》勘误

## 勘误提交格式

请大家在提交勘误时，先查看问题在本页面是否已经存在，如果不存在，请以如下格式进行提交，方便问题跟踪与记录。

格式：

+ 印数：第x印（见扉页）
+ 位置：第xx页第xx行
+ 问题：问题内容
+ 建议：建议内容

范例：

+ 印数：第一印
+ 位置：第87页 访问控制 小节
+ 问题：错别字pbulic
+ 建议：改为public

## 勘误内容

### 第一印

|提交人员|位置|问题|修改|
|----|----|----|----|
|bigfacecat1208|第70页第1行|字典的下表操作|修改为“字典的下标操作”|
|bigfacecat1208|第87页 访问控制 小节|错别字pbulic|改为public|
|bigfacecat1208|第98页倒数第3行|“二进制版本是storybordc“中storybordc拼写错误|修改为“二进制版本是storyboardc“|
|bigfacecat1208|第100页第2行|"Project Nevigator"中拼写错误|修改为“Project Navigator”|
|bigfacecat1208|第100页第4行|“Axes Idependently”拼写错误|修改为“Axes Independently”|
|bigfacecat1208|第101页第1行|“Text Failed”中拼写错误|修改为“Text Field”|
|bigfacecat1208|第102页最后1行|base64编码|应与上下文统一，改为Base64|
|bigfacecat1208|第108页第5行|小标题“CodeSignature目录”错误|修改为“_CodeSignature目录”|
|bigfacecat1208|第110页第11行|"下来看一下通用……"中缺个“面”字|加上“面”字|
|bigfacecat1208|第156页第2、4行|框架目录中System目录前应加“/”|修改为"/System"|
|bigfacecat1208|第184页倒数第3行|”mian.c源文件“拼错了|改为“main.c”|
|bigfacecat1208|第186页第6行|C语言的多行注释写错了|改为“/* */”|
|bigfacecat1208|第187页表5-1中第4行|“-static时”后面内容中标点符号错误使用了“、”|改为“,”|
|bigfacecat1208|第193页第10行|助记符的英文拼写错误|改为mnemonic|
|bigfacecat1208|第196页5.4.5节的第3行|“分为两堆和栈个部分”为病句|改为“分为堆和栈两个部分”|
|bigfacecat1208|第199页第1行|“应为”写错了|改为“因为”|
|bigfacecat1208|第200页第13行|“macoOS”拼错了|改为“macOS”|
|bigfacecat1208|第249页第2行|"GBD"拼错|改为“GDB”|
|bigfacecat1208|第256页第11行和17行|“~/lldbinit”写错了|改为”~/.lldbinit“|
|bigfacecat1208|第262页第3行|"cm01程序"写错了|改为”cm02程序“|
|bigfacecat1208|第263页第6行|”NSAAlert函数“拼错了|改为”NSAlert“|
|bigfacecat1208|第286页倒数第9行|“ptrace函数一个有4个参数”中个字写错了|改为“一共”|
|bigfacecat1208|第336页正文倒数第4行|“esi寄存器存放后面的isASCII参数”中寄存器写错了|改为"edx"|
|bigfacecat1208|第351页倒数第2行、第359页第3行、360页、361页、362页|标题与内容中的“Swizzing”拼错了|改为Swizzling|
|bigfacecat1208|第398页第10行|路径名中Applicaton拼错|改为Application|
|bigfacecat1208|第432页倒数第7行|刚接解|改为“刚接触”|
|bigfacecat1208|第458页倒数第4行|碰盘管理|磁盘管理|
|飘云|第94页倒数第5行|Visual Studo Code|修改为Visual Studio Code  |
|飘云|第97页第4、5行|Visual Studo Code|修改为Visual Studio Code  |
|飘云|目录3.5.4以及所有引用到的地方|Visual Studo Code|修改为Visual Studio Code|
|飘云|第229页倒数2、3行|IDA Pro菜单Edit->Patch Pragma|修改为Patch Program|
|飘云|第274第1行|in th license|in the license|
|飘云|第279第2行|Evaluate free|Evaluate for free|
|飘云|第279第4行|Dacula风格|Darcula风格|
|飘云|第409页倒数第9、10行|oxCC|修改为0xCC|
|everettjf|第4页 “提示”文字|./configure --disable-x11-text-mode|./configure --disable-x11-textmode （textmode之间没有-）|
|everettjf|第191页第3行|比如EAX寄存器赋值为1，则整个REX寄存器也会被赋值为1|REX改为RAX|
|everettjf|第196页第9行（5.4.5节第3行）|这个区域分为两堆和栈个部分|这个区域分为堆和栈两个部分|
|didongke|第351页9.4节|9.4节有四个小节（4种方法），但前面说主要有3种方法，而且两种方法前面加了小方块，会误以为是第一种方法的子方法。|修改为4种方法，SymbolTable Hook下加上Inline Hook，`DYLD_INSERT_LIBRARIES`前加上小方框|
|didongke|第355页倒数第1行|ishhook写错了|改为fishhook|
|didongke|第359页9.4.4节的第2行|调用一个方法Objective-C|改为调用一个Objective-C方法|
|chenxiangfang|第68页表3-2|Int无符号|Int改为有符号|
|Huang-Libo|第20页第4行|Base64加密|改为Base64编码|
|xuanInitial|76页16、18行|sort()|改为sorted()|
|0xwuyan/eltonto187|第56页第11行|MyObject.m文件的#import "Shape.h"|改为#import "MyObject.h"|
|0xwuyan/eltonto187|第57页第18行|-(NSString*)toString;{ 多了一个分号;|去掉分号;|
|0xwuyan|第63页 表3-1属性参数 原子性 atomic 说明|对方问速度有影响|改为对访问速度有影响|
|hyperiris|第102页第2行|代码试图|改为代码视图|
|hyperiris|第93页倒数第5行|在Objective中使用外部|改为在Objective-C中使用外部|
|eltonto187|第36页第22行|if((fwrite(&currentHeader, sizeof(currentHeader), 1, fp)) != sizeof(currentHeader))|改为if((fwrite(&currentHeader, 1, sizeof(currentHeader), fp)) != sizeof(currentHeader))|
|eltonto187|第35页倒数第1行|if (argc < 1)|改为 if (argc < 2)|

