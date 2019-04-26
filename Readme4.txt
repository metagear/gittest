#项目代号VV，新写业务代码以VV开头

=================================
#公共能力
##打印日志 VVLogError VVLogWarn VVLogAppInfo
##SSO收发包 VV/Public/NetWork/ProtocolFrame/BizNetwork/VVBizNetworkLogic.h
##个人账号信息 /VV/Service/UserInfoService/VVAccountService.h
##个人资料 /VV/Service/UserInfoService/VVUserInfoService.h
##数据上报 VV/ThirdParty/Report/DataReport/VVDataReport.h
##HTTP网络 VV/ThirdParty/QQHttp
##App级别大配置数据Model信息存储 VV/Service/ConfigService/VVCfgService.h
##登录用户级别大配置数据Model信息存储 VV/Service/ConfigService/VVCfgService.h
##小数据存储 VV/Service/ConfigService/VVUserDefaults.h
##数据库存储例子 /VV/Public/Cache/VVCacheService.h (具体使用可参照VVStorageService+RedDot)
##本地ICON加载使用LOAD_DEFAULT_ICON_USE_POOL /VV/Public/Utils/VVImagePoolUtil.h 图片放在resource/default
##转场动画基类:VVSlideDismissViewController,present时放大动画,dimiss跟随手势缩小,松手回到原位置
==================================

业务代码负责人：http://tapd.oa.com/kandian/documents/show/1020406502001062875

==================================

注意：这里有些小能力并没有列出来，后续有需要用到某些能力，可以搜一下工程中是否有相应代码。

--SDK
微信SDK版本：1.8.2
QQSDK版本：3.3.3.0
微博SDK版本：3.2.2

--WNS  OK
----登录 VV/Service/LoginService
----个人资料 /VV/Service/UserInfoService/VVUserInfoService.h
----收发包 VV/Public/NetWork/ProtocolFrame/BizNetwork/VVBizNetworkLogic.h

--数据库 ITCommon/ThirdParty/GYDataCenter
----存储 VV/DataCenter

--监控上报
----业务上报VV/ThirdParty/Report/DataReport/VVDataReport.h
----监控VV/ThirdParty/Report/VVDataReportDefine.h

--WebView VV/Modules/Webview
----JS接口
----TBS

--分享  VV/Biz/ShareKit

--播放器

==================================



==================================
==暂时没有加入的==

--流量统计 TBFlowCounterDataService

----王卡流量接入(需要预研)
