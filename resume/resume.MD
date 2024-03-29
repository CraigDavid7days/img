# 联系方式

* 手机：130****7293
* Email：11****8461@qq.com
* QQ/微信号：11****8461

# 个人信息

* 陈炎坤/男/1993
* 本科/温州大学计算机系
* 工作年限：3年
* Github：https://github.com/w1lkin
* 期望职位：java开发工程师
* 期望薪资：税前月薪13k~18k，特别喜欢的公司可例外
* 期望城市：杭州

# 工作经历

## 杭州销冠网络科技有限公司 （ 2016年6月 ~ 2018年6月15日）
[杭州销冠网络科技有限公司](https://www.tops001.com)创办于2012年10月，旨在通过移动互联网创新，打造房产品及服务的交易全流程信息化，提升房产交易效率
销冠是中国最大的不动产及服务交易平台，主要有4大产品：销冠管家、销冠经纪、销冠新房、销冠金服

### BOPS项目
bops全称Back Office Process System ，即后台办公流程系统，是销冠的后台办公系统，管理产品业务在平台的上架、交易确认、资金结算。主模块包括：企业、账户、合同、交易、结算、费用、发票、统计、金融。分为2大类管理：交易前、交易后。平台的交易分布在各业务线中，最后都会流转到后台中进行管理。

在bops重构期间，我负责金融模块的数据库设计及编码实现，以及对合同的改造和维护。
在此期间，遇到的问题主要包括以下几点：
1. 合同涉及到的交易结算规则复杂多样，通过设计合同计算引擎解决
2. bops是后台管理系统，涉及到财务、交易等重要的敏感数据，重构时遇到新老系统如何做到无缝切换，尤其是新老数据如何迁移的难题。新老系统无缝切换通过服务分批、分城市上线；新老数据迁移通过多角度、多维度来验证导入数据的准确性
3. bops涉及到众多审核流，每个流程复杂多样，通过使用流程引擎activiti解决

通过bops项目，让我对于公司业务有了更加深刻的理解，同时对于自己的java的技术水平也有了很大程度的提高。

主要技术实现：Springboot，CXF，MyBatis，Activiti等

项目地址：http://bopsadmin.apitops.com/

### 销冠金服项目
销冠金服作为销冠主要产品之一，通过对接不同的资方，在销冠金服较为完善的业务管理系统和风控体系下，满足不同客户的不同的贷款业务(包括赎楼贷、成长基金、销冠零钱、包销、保理快结等)。

我作为这个项目主程之一，参与了整个项目的开发，包括从项目搭建开始以及后期各个子模块的开发和维护。

在此遇到的难题主要包括：
1.  金服对于风控要求较高，通过对接第三方风控（例如同盾、白骑士等）以及金服系统自有风控体系联合解决
2.  excel导出表格格式较为复杂多变，通过jxls自定义模板解决excel导出格式复杂问题
3.  审核流复杂多样，通过使用流程引擎activiti解决

通过销冠金服项目的磨练，让我对于整个项目开发流程有了更加清晰透彻的理解，以及对于销冠金服的业务有了较深的理解。

主要技术实现：Spring，CXF，MyBatis，Activiti，Elasticsearch，Mongodb等

项目地址：
* 后台地址：http://jf.apitops.com
* 官网地址：http://www.topsfin.com

### 其他项目
销冠圈项目作为公司内部员工交流互动的平台，主要功能包括：
* 拓展人员通过app记事沉淀关联经纪人数据及KPI数据化管理
* 销冠内部KPI及工作客户的管理平台
* 销冠小伙伴们的内部交流社区，销冠公司内部公告、活动等官方发布

我参与到这个项目的项目搭建和初期的数据库设计，以及前几期的项目开发。

项目地址：销冠圈(ios，android)，仅限公司内部使用，不提供下载

## 温州温商贷互联网金融服务有限公司 （ 2015年11月 ~ 2016年5月（大四））
[温商贷](http://www.wsloan.com/)是国内前20强互联网理财平台，公司为有闲散资金需求的投资人和有融资需求但缺乏融资渠道的借款人搭建桥梁。采用O2O结合P2P模式，借助线下业务团队发掘优质借款人，经过严格的风控审核程序和抵押手续将项目信息移植到线上，供全国各地的线上投资人投标。

### 温商贷BBS项目 
我在此项目中负责部分模块前后端代码实现。通过这个项目的经历，我意识到良好的代码风格以及注释习惯对于后续的维护相当重要。

主要技术实现：Winform

项目地址：http://bbs.wsloan.com/

### 温商贷活期项目
我在此项目中负责活期服务几个模块代码编写以及部分前端页面制作。在这个项目中，我首次接触到WCF的概念，并在开发过程中对WCF有了较为深刻的理解，同时对于数据库存储过程和函数有了一定的认识。

项目地址：http://www.wsloan.com/hqlc.aspx

温商贷活期项目是我第一个使用WCF技术的项目，之后参与的采用WCF技术的项目包括：
1. 温商贷app消息推送服务
2. 温商贷服务控制中心服务
3. 温商贷会员服务
4. 温商贷积分服务
5. 温商贷积分商城服务
6. 温商贷体验金服务
7. 温商贷投标服务

通过对温商贷网站进行服务颗粒化地改造，对WCF的研究也不断深入，并进行了一定的封装；对于数据库存储过程和函数的编写也更为得心应手。

### 温商贷数据控制中心项目 
温商贷数据控制中心项目-通过对用户行为进行采集，分析用户各方面数据以及通过对WCF服务调用情况数据进行采集，分析服务健康度和调用情况。

我在此项目中负责数据采集，并对采集到的数据通过合适的图表进行展示，使得网站运营数据一目了然，方便领导进行相应的策略制定。

在此项目中遇到的主要技术难题包括：
1.  数据库查询：当单表数据量达到千万级别时，合理地使用SQL语句变得相当重要。
2.  数据库优化： 当单表数据量非常大时，通过表分区，数据库缓存等技术进行数据库优化。
3.  C# WebSocket：使用[Fleck](https://github.com/statianzo/Fleck)插件实现服务器端WebSocket服务器。
4.  图表制作：使用[Echarts](http://echarts.baidu.com/)制作所需要的图表。

在此项目中，我对于T-SQL语句的掌握有了很大的提升，对数据库存储过程和函数的编写更加熟练，对数据库优化也有了相应的认识，以及对于ECharts的使用得心应手。

项目地址：网站挂在温商贷内部服务器上，外网无法访问

## 温州联线网络科技公司 （ 2014年3月 ~ 2015年11月（大三-大四））
公司产品主打微信营销，与著名互联网金融公司温商贷、整形医院艺星、温州苏宁、温州移动、加多宝等有长期合作协议，业务包括但不限于微信公众平台日常吸引粉丝、维护粉丝活跃的线上活动开发。

### 众创众享项目
我在此项目中负责前后端技术转移、政策等模块的实现。

主要技术实现：.NET MVC，BootStrap

项目地址：http://www.zczxcloud.com/

### 温州市党建信息平台项目
我在此项目中负责手机端代码实现，主要包括会议签到、党费缴纳、党员关系等模块，遇到的主要问题包括：
1.  js跨域问题，通过jsonp方式解决
2.  webapp打包生成，项目通过App Framework写成，结合phonegap 快速生成安卓APP和IOS APP。
3.  手机端支付功能实现。结合文章[phonegap（cordova）移动支付宝接口调用](http://blog.csdn.net/sirm2z/article/details/49614553)实现

经过这个项目，我解决问题的能力得到显著提升，同事和领导也认为我的进步非常大。

项目地址：http://dangjian.wificun.cn/（电脑端）

手机端：民情E通 APP

### 其他项目
公司前期运营微信公众号“游意思”平台，我独立开发了该平台的几款微信游戏：
1.  围住神经猫：结合网上热门游戏-围住神经猫案例，通过Adobe的CreateJS制作，做了屏幕自适应以及相关游戏逻辑优化。
2.  经典飞机：结合微信小游戏“微信打飞机”案例，通过原生js写成，对js对象有了较为深刻的理解。

项目地址：http://yys.wificun.net/home/yysindex

## 温州红点科技有限公司 （ 2012年12月 ~ 2014年1月-（大一-大二））
微信公众号平台“掌上大学”项目，温州高教园区本地化平台“掌上茶山”项目的前端开发。项目由我校创业办的辅导员提出最初构想，并指导三名学生实施，项目初具规模时注册了公司。项目内容是为高教园区数万学生搭建微信公众平台，集中园区中大部分商铺以提供优惠便捷的餐饮娱乐服务，同时，接入教务系统以为学生群体特别提供查课表、考场、成绩等功能。

我在项目中负责的工作有：
1.  负责“掌上大学”PC端及微信端官网制作，以及各个子功能的实现。
2.  负责“掌上茶山”商铺界面，包括团购、店铺列表、订餐、下单、点评等前端页面开发。

项目地址：http://www.wxhand.com/

# 开源项目和作品

## 开源项目
* [spring-boot-seed](https://github.com/w1lkin/spring-boot-seed)：对所学java知识巩固提高并拓展    项目地址：https://github.com/w1lkin/spring-boot-seed

# 技能清单
以下均为我熟练使用的技能：
![java web开发技术栈](https://raw.githubusercontent.com/w1lkin/img/master/spring-boot-seed/java-web%E5%BC%80%E5%8F%91%E6%8A%80%E6%9C%AF%E6%A0%88.png)

---      
# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。
  