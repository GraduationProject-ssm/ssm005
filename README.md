# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# ssm005基于SSM框架的购物商城系统+jsp

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)]()


# 绪论
## 1.1 选题背景
网络技术和计算机技术发展至今，已经拥有了深厚的理论基础，并在现实中进行了充分运用，尤其是基于计算机运行的软件更是受到各界的关注。计算机软件可以针对不同行业的营业特点以及管理需求，设置不同的功能，可以符合各个行业的实际运营要求，其快速便捷的信息处理模式已经可以让信息的管理者从繁琐的工作中得到解脱，还可以实现数据的易维护和安全性。加上现在人们已经步入信息时代，所以对于信息的宣传和管理就很关键。因此信息化管理模式也是当今的管理趋势。对于商城购物信息，如果仍使用旧办法进行，将会影响其在行业中的竞争力，也很容易被时代淘汰，所以商城购物信息的管理计算机化，系统化是必要的。设计开发购物商城系统不仅会节约人力和管理成本，还会安全保存庞大的数据量，对于商城购物信息的维护和检索也不需要花费很多时间，非常的便利。
## 1.2 选题意义
购物商城系统在实际运用中，对管理员的综合素质的提升也有帮助。因为购物商城系统在减轻了商城购物信息管理人员的工作量的同时，还可以让他们把节省出来的时间用来充实自己，提升个人能力，这样才可以充分发挥购物商城系统提供的服务，让购物商城系统显示数据信息的同时，也可以快速完成数据处理，提升服务水平。而且购物商城系统开发需要投入的成本较低，但是后期运用中，会产生大量效益，尤其是购物商城系统在进行高负荷运转时，还可以保证数据处理的质量与数据安全，通过对处理工作的流程的优化，可以节省传统模式需要投入的人力和资金，从而降低信息管理的成本。另外，购物商城系统在让商城购物信息规范化的同时，也能及时通过数据输入的有效性规则检测出错误数据，让数据的录入达到准确性的目的，进而提升购物商城系统提供的数据的可靠性，让系统数据的错误率降至最低。
## 1.3 研究内容
按照设计开发一个系统的常用流程来描述系统，可以把系统分成分析阶段，设计阶段，实现阶段，测试阶段。所以在编写系统的说明文档时，根据系统所处的阶段来描述系统的内容。

绪论：这是对选题的背景，意义等内容做出介绍。

系统开发技术：这是对系统即将使用的技术，包括使用的工具，编程的语言等做出介绍。

系统分析：这是对系统做出分析，包括投资前期必备的可行性分析，包括对用户调研获取的需求，包括系统运行具备的性能等内容做出介绍。

系统设计：这是对系统进行设计，包括运用绘图工具设计的系统功能结构，包括设计的在数据库中要创建的数据表的存储结构等内容做出介绍。

系统实现：这是对系统进行编码实现。包括实现的系统各个模块的运行效果等内容做出介绍。

系统测试：这是对编制的系统进行测试。包括功能的测试等内容做出介绍。




# 2 系统开发技术
这部分内容主要介绍本系统使用的技术，包括使用的工具，编程的语言等内容。
## 2.1 Java语言
Java语言自公元1995年至今，已经超过25年了，依然在软件开发上面有很大的市场占有率。当年Sun公司发明Java就是为了发展一门跨平台的高级编程语言，让程序开发人员专注于程序开发过程，不需要关注服务器是属于哪个平台，因为跨平台的特性让语言发展的很迅速。Java的发展，吸收了C++这些语言的优点，因为新生事物一般就是解决老旧事物一些痛点的，虽然Java也有很多缺点，但是起码也算是一种发展方向。学习Java不需要太多的指针这些理念，也不用学习太过复杂的数据结构理论，比如什么堆栈这些概念，除非某些特殊行业对这些要求相当严谨之外，一般用Java开发程序是不用考虑各种各样的数据结构的。因为Java属于一种强类型语言，已经对各种数据定义了各种相应的类型。Java对数据类型定义分为两大种，一种是基本类型，含有8个基本属性，另一个是包装类。基本类和包装类从根本的定义上，都有很明显的区分，计算机运行也会有很明显的差别，如果用错了会编译错误还会影响运行效果的，Java的各种优点只需要按部就班的学习使用即可。
## 2.2 SSM框架
本课题开发的应用程序主要采用的框架技术是SSM，是Java语言的一种框架集合的简称，目前在Java语言方面，主要有两大分支，一个是主攻Java语言，学习了Java基础之后，会有很多Java进阶框架进行学习，主要是针对应用程序后台进行开发设计，另一方面是转行去学习安卓语言，主要是做安卓的前端设计方面，虽然也是Java语言，但是主要去学习安卓平台的各种架构和框架了。但是不管前端应用如何，SSM框架主要是针对服务端方面进行开发的一个主流框架集合。针对于传统的SSH框架的臃肿，配置繁琐，不管是开发还是二次开发都会造成时间上大量的浪费，并且学习上面也不能有效衔接，需要去适应框架的各种设计，而框架设计比较死板，容易出错。SSM框架是当前最流行的，告别了繁琐的配置，让配置更加灵活，让数据操作更加方便，选择SSM框架进行开发感觉是很合适的。
## 2.3 MYSQL数据库
关系型数据库设计，对于数据库字段类型的设计以及字段长度的设计，都无时无刻的影响着后续程序开发后大量数据操作的运行效率。关系型数据库对不同的字段类型都有解释，本着课题所需的应用程序开发，寻找最适合的关系型数据库，基本上都有考虑。关系型数据库发展至今也有几十年了，优胜劣汰导致到现在还依然存在的关系型数据库其实并不多，基本上也都能满足应用程序的功能所需，所以要从其他方面来进行考虑数据库的选择。从安装维护上面考虑，SQL Server数据库有好几个G的安装包，并且安装过程中会安装很多不需要的功能，非常占用资源。Oracle数据库不比SQL Server安装包小，并且安装也会出现很多问题，对于课题所需来讲，没必要这么麻烦，并且安装还需要各种激活，只有MySQL数据库完全适合，几十兆大小的安装包，运行起来压力不大，毕竟开发电脑上还有很多其他有用的东西，而且完全免费，所以选择了MySQL数据库作为首选数据库。
# 3 系统分析
这部分内容虽然在开发流程中处于最开始的环节，但是它对接下来的设计和实现起着重要的作用，因为系统分析结果的好坏，将直接影响后面环节的开展。
## 3.1可行性研究
影响系统开发的因素有很多，比如开发成本高就不适合开展，或者是开发时间超过了预期，也不适合开展等等。所以，在正式作出开发决策前，研究系统可行性问题，从经济，时间，操作等角度论证系统是否可以开展。
### 3.1.1经济可行性
购物商城系统可以简化工作流程，提供信息处理功能，并可以长期保存数据，在后期的数据查询与编辑中耗时少，提升信息管理效率，其带来的收益比较可观。对于本系统开发，无论是开发需要使用的计算机，还是开发工具等投入的成本很低，计算机是机房的电脑，开发工具是从网上下载安装的，并没有收取费用。
### 3.1.2时间可行性
购物商城系统是作为本人毕设项目的一个作品，学院也充分预留了制作时间，并且在每个时间段，都安排了相应的任务，所以根据这个时间安排开展工作，是可以对本系统进行设计完成的。
### 3.1.3操作可行性
随着电脑的普及，已经有很多人可以独立操作电脑了。而本系统就是在配置了运行环境的电脑上运行，其功能简单，省去了很多繁琐的操作逻辑，使用者通过页面导航可以直接进入功能操作区，所以稍微懂点电脑的人，都可以轻松完成系统的使用。

综上所述，本系统可以开展接下来的工作了。
## 3.2系统性能分析
为了降低本系统在实际使用中的出错率，就需要分析系统具备的性能。常见的可以评估系统的性能的指标有安全性，易用性，健壮性等。
### 3.2.1系统易用性
系统提供的信息和服务都有特定的用户群，所以，一个容易操作的系统相比一个不方便使用的系统来讲，用户还是更加青睐于使用方便的系统。所以系统具备易用性就显得非常重要。
### 3.2.2系统健壮性
系统在与用户进行交互过程中，面对用户的误操作行为，系统应该有相应的处理这种问题的反馈机制，而不是进入系统崩溃状态。系统中设置了很多的功能，在应对系统中某个功能出现异常情况时，系统的其它功能还是可以让用户使用。这就是系统健壮性的体现。
### 3.2.3系统安全性
保存在系统里面的数据，都是比较重要的系统资源，一旦这些资源泄露，不仅会有财产损失，还会丧失很多客户。所以，系统里面的数据要随时都处于安全的环境中，因此就需要采取措施保证数据安全，比如设置登录功能，使用安全验证技术引导条件用户进入指定页面，而让非条件用户停留在登录页面，不能访问系统。
## 3.3 系统流程分析
软件开发设计的思想始终贯穿本系统，其开发流程见下图。前期需要进行功能分析，功能设计，还有对系统后台支持数据库的设计，利用编码技术对设计的系统进行实现，然后检测和完善。

![](/md/blog.001.png)

图3.1系统开发流程图

访问者之所以可以访问购物商城系统，主要是其数据库有该访问者的记录信息，这个记录是通过注册进行写入的数据。注册流程见下图。每当访问者进行购物商城系统注册时，其登记的每条记录都会在系统后台进行逐个判断。这个判断规则是提前设置的。一旦该访问者的登记信息在数据库中保存，即代表该访问者成为购物商城系统中的一份子。

![](/md/blog.002.png)

图3.2 注册流程图

访问者操作系统，前提是需要验证身份，而登录功能的设置就是把本系统的用户引导进入后台操作区，把不是本系统的用户拒之门外。其流程见下图。

![](/md/blog.003.png)

图3.3 登录流程图
## 3.4系统功能分析
在明确系统的用途，以及系统的目标用户群后，可以对本系统的功能进行设置，可以获取调研用户对功能的要求，也可以对市场上同类系统进行分析和总结，得出本系统的功能。

购物商城系统设置了管理员权限，其用例图见下图。管理员登录进入本人后台之后，管理商品和用户，查看和回复用户对商品的评价，管理不同状态的订单。

![](/md/blog.004.png)

图3.4 管理员用例图

购物商城系统设置了用户权限，其用例图见下图。用户管理收货地址，管理不同状态的订单，收藏商品，评价商品。

![](/md/blog.005.png)

图3.5 用户用例图






# 4 系统设计
当前，系统的类型有很多，从系统呈现的内容来看，系统的类型有社交类，有商业类，有政府类，有新闻类等。那么，在众多系统类型中，先明确将要设计的系统的类型才是系统设计的首要工作，然后在此基础上明确系统的用户群，功能等，针对这些信息设计出具有独特体验和视觉的系统。如此才能让系统比较具有特色，也能够在众多相似系统中给用户留下深刻印象。
## 4.1系统目标
本系统在功能制定上，严格参照用户的要求，但是在设计本系统时，也要满足易操作，使用便利的设计要求。由此，设计出一个规范化并且符合用户需求的系统，一定要达到下述系统目标。

第一个系统目标：用户与系统之间的操作方式是基于人机对话，可视化界面的设计除了美观性之外，也具备友好性。可视化界面提供的各类信息符合准确性，可靠性的要求，并能够方便用户灵活查看。

第二个系统目标：用户与系统交互产生的数据，要严格规范的保存在数据库里，无论是后期管理人员查找与管理，都要确保数据安全。

第三个系统目标：实现用户需求的功能。根据对用户的调查得出的功能需求，完成购物商城系统的设计与实现。

第四个系统目标：在必要环节，对用户登记的数据进行检查，包括数据长度，以及数据输入类型等的检查，发现错误及时反馈，引导用户规范登记数据。常见的有密码修改，注册登录，用户资料填写等环节的数据核验。

第五个系统目标：设计开发本系统，需要尽最大努力，在系统具备易操作的特点外，也要求系统于后期使用中，维护方便，让系统具备易维护的特点。

第六个系统目标：本系统在交付用户使用时，可以达到运行稳定的目标，另外，系统具备安全性，也符合可靠性的条件，用户可以放心使用。
## 4.2功能结构设计
前面所做的功能分析，只是本系统的一个大概功能，这部分需要在此基础上进行各个模块的详细设计。

设计的管理员的详细功能见下图，管理员登录进入本人后台之后，管理商品和用户，查看和回复用户对商品的评价，管理不同状态的订单。

![](/md/blog.006.png)

图4.1 管理员功能结构图

设计的用户的详细功能见下图，用户管理收货地址，管理不同状态的订单，收藏商品，评价商品。

![](/md/blog.007.png)

图4.2 用户功能结构图
## 4.3数据库设计
相比非关系型数据库来说，目前市场上使用率比较高，并且易于维护的数据库，当数关系型数据库了。这个数据库主要是基于关系模型的方式来对数据信息进行组织。也就是常见的二维表模型。可以说二维表和二维表之间的相互联系就构成了关系型数据库。
### 4.3.1数据库E-R图
为了更好地保存购物商城系统产生的数据，就需要在数据库的设计阶段对E-R模型进行建立，以及完成数据库中的表结构的创建。之所以要单独完成数据库的设计，主要有以下几点原因：

第一点：防止代码冗余；

第二点：防止占用过多内存；

第三点：提升数据库的整体性能，方便程序开发以及数据更新；

第四点：保证数据的完整性；

本部分内容主要在于建立本系统的E-R模型，需要先收集数据，然后根据数据库实现的思路，对用户的需求进行分析，这期间需要对实体，属性，还有关系进行标识，为绘制E-R模型做好充足准备。同时，在作图中，也要注意作图规范，注意每个符号的正确使用。

（1）设计的订单实体，其具备的属性见下图。订单实体包括的属性值有商品名称，商品图片，支付类型，状态，地址，用户等信息。

![](/md/blog.008.png)

图4.4 订单实体属性图

（2）设计的商品实体，其具备的属性见下图。商品实体包括的属性值有品牌，规格，原价，数量，商品分类等信息。

![](/md/blog.009.png)

图4.5 商品实体属性图

（3）设计的用户实体，其具备的属性见下图。用户实体包括的属性值有用户姓名，密码，联系电话，电子邮箱等信息。

![](/md/blog.010.png)

图4.6 用户实体属性图

（4）设计的购物车实体，其具备的属性见下图。购物车实体包括的属性值有商品名称，用户，创建时间，购买数量，单价等信息。

![](/md/blog.011.png)

图4.7 购物车实体属性图

（5）设计的各实体间关系见下图。

![](/md/blog.012.png)

图4.8 实体间关系E-R图
### 4.3.2 数据库表结构
为了设计出结构合理，性能优良的数据库，在设计数据库时，需要遵循三大范式：

第一范式：确保数据表当中的每列所代表的字段值都不能再进行分解了；

第二范式：在满足第一范式基础上，让数据表中每列与主键相关；

第三范式：在满足第二范式基础上，确保每列数据直接与主键相关，不是间接相关。

从上面的表述中可以看出，这三大范式，在等级上还是有区分的，最低等级的就数第一范式，最高等级的就是第三范式，趋于两者中间的是第二范式。总之，数据库设计按照这三大范式进行，可以简化设计过程，并且还会减少数据冗余，对于数据检索效率的提升也很有帮助。

（1）购物车信息表：用于保存购物车的数据。包括购买数量，商品名称，商品图片，单价等信息。

表4. 1购物车信息表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|tablename|varchar(200)|是|shangpinxinxi|商品表名|
|userid|bigint(20)|否||用户id|
|goodid|bigint(20)|否||商品id|
|goodname|varchar(200)|是|NULL|商品名称|
|picture|varchar(200)|是|NULL|图片|
|buynumber|int(11)|否||购买数量|
|price|float|是|NULL|单价|
|discountprice|float|是|NULL|会员价|
（2）订单信息表：用于保存用户购买商品的数据。包括商品名称，商品图片，购买数量，状态，支付类型等信息。

表4. 2订单信息表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|orderid|varchar(200)|否||订单编号|
|tablename|varchar(200)|是|shangpinxinxi|商品表名|
|userid|bigint(20)|否||用户id|
|goodid|bigint(20)|否||商品id|
|goodname|varchar(200)|是|NULL|商品名称|
|picture|varchar(200)|是|NULL|商品图片|
|buynumber|int(11)|否||购买数量|
|price|float|否|0|价格/积分|
|discountprice|float|是|0|折扣价格|
|total|float|否|0|总价格/总积分|
|discounttotal|float|是|0|折扣总价格|
|type|int(11)|是|1|支付类型|
|status|varchar(200)|是|NULL|状态|
|address|varchar(200)|是|NULL|地址|
（3）商品信息表：用于保存商品的数据。包括商品名称，商品分类，数量，品牌，详情，规格等信息。

表4.3 商品信息表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|shangpinbianhao|varchar(200)|是|NULL|商品编号|
|shangpinmingcheng|varchar(200)|是|NULL|商品名称|
|shangpinfenlei|varchar(200)|是|NULL|商品分类|
|shuliang|varchar(200)|是|NULL|数量|
|pinpai|varchar(200)|是|NULL|品牌|
|guige|varchar(200)|是|NULL|规格|
|xiangqing|longtext|是|NULL|详情|
|fengmian|varchar(200)|是|NULL|封面|
|clicktime|datetime|是|NULL|最近点击时间|
|clicknum|int(11)|是|0|点击次数|
|price|float|否||原价|
|discountprice|float|是|NULL|折扣价|
|flag|int(11)|是|NULL|是否上架(1:上架,2:下架)|
（4）管理员信息表：用于保存管理员的数据。包括用户名，密码，新增时间等信息。

表4. 4 管理员信息表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|username|varchar(100)|否||用户名|
|password|varchar(100)|否||密码|
|role|varchar(100)|是|管理员|角色|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|新增时间|
（5）用户信息表：用于保存用户的数据。包括用户账号，用户联系电话，用户电子邮箱，用户性别，用户密码等信息。

表4.5 用户信息表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|yonghuzhanghao|varchar(200)|否||用户账号|
|yonghuxingming|varchar(200)|否||用户姓名|
|mima|varchar(200)|否||密码|
|xingbie|varchar(200)|是|NULL|性别|
|lianxidianhua|varchar(200)|是|NULL|联系电话|
|dianziyouxiang|varchar(200)|是|NULL|电子邮箱|
|money|float|是|0|余额|


# 5 系统实现
在此部分内容中，主要通过系统功能的运行效果图展示前面设计的最终结果。系统实现对编制人员的技术能力有较高要求，因为需要他们使用编程的方式去实现系统设计的方案。
## 5.1 管理员功能实现
### 5.1.1 商品信息管理
管理员权限中的商品信息管理，其运行效果见下图。管理员维护商品资料，能修改与删除。也能登记本页面没有的商品资料。其中商品信息是由商品分类，商品详情介绍，商品品牌，商品数量，商品的价格，商品的编号和名称等构成。

![](/md/blog.013.png)

图5.1 商品信息管理页面
### 5.1.2 用户管理
管理员权限中的用户管理，其运行效果见下图。用户可以注册提交信息，也可以让管理员在后台添加用户，维护用户资料，能修改与删除。用户信息包括用户姓名，用户联系电话，用户电子邮箱，用户密码等信息。

![](/md/blog.014.png)

图5.2 用户管理页面
### 5.1.3 商品评价管理
管理员权限中的商品评价管理，其运行效果见下图。用户评价商品，待管理员查看后，可以回复。商品评价信息是由商品名称，评论内容，回复内容，用户手机号，用户名称等组成。

![](/md/blog.015.png)

图5.3 商品评价管理页面
### 5.1.4 已完成订单
管理员权限中的已完成订单，其运行效果见下图。管理员管理处于不同状态的订单，查询已完成订单，也能直接删除已经完成的订单信息。

![](/md/blog.016.png)

图5.4 已完成订单页面
## 5.2 用户功能实现
### 5.2.1 商品信息
用户权限中的商品信息，其运行效果见下图。用户在本页面可以操作的功能比较多，可以收藏，评价页面内的商品，可以直接购买，也能暂时加入购物车保存商品。

![](/md/blog.017.png)

图5.5 商品信息页面
### 5.2.2 购物车
用户权限中的购物车，其运行效果见下图。购物车帮助用户暂时保存购买的商品，方便用户一次性下单购买多种商品。

![](/md/blog.018.png)

图5.6 购物车页面
### 5.2.3 提交订单
用户权限中的提交订单，其运行效果见下图。下单支付前，收货地址和购买的商品需要再次核对清楚，最后支付订单。

![](/md/blog.019.png)

图5.7 提交订单页面
### 5.2.4 已支付订单
用户权限中的已支付订单，其运行效果见下图。用户对订单明细进行查看，可以选择对某些误购买的商品进行退款。

![](/md/blog.020.png)

图5.8 已支付订单页面
### 5.2.5 我的地址
用户权限中的我的地址，其运行效果见下图。用户管理收货地址，能修改与删除。

![](/md/blog.021.png)

图5.9 我的地址页面

# 系统










