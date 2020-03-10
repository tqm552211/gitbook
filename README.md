请提供本文档编写过程中所有主要参考资料列表（文档或者链接）

| 版本 | 作者   | 发布日期   | 备注                                                         |
| :-- | :------ | :---------- | :------------------------------------------------------------ |
| 1.1  | 范松灿 | 2019-08-27 | 定义甬上与三方交互基础接口规范                               |
| 1.2  | 陈玉石 | 2019-09-22 | 修改酒店、机票、火车票的下单接口；<br/>增加了结算价信息，修正了数据结构；增加改签单信息。 |
| 1.3  | 陈玉石 | 2019-09-23 | 修改酒店、机票、火车票的下单接口；<br/>增加了用户信息、佣金参数配置、所有的价格项明细和汇总。 |
| 1.4 | 陈玉石 | 2019-09-24 | 修改退票接口；<br>修改订单详情接口； |
| 1.5 | 陈玉石 | 2019-10-08 | 修改酒店创单接口<br/>增加订单详情接口 |
| 1.6 | 陈玉石 | 2019-10-10 | 修改退款接口<br/>订单详情接口返回子订单中增加了退款状态、改签状态 |
| 1.7 | 陈玉石 | 2019-10-11 | 增加创单接口的公式 |
| 1.8 | 陈玉石 | 2019-10-11 | 对三个创单和订单详情接口都做了修改，如下：<br/>salePrice改为settlePrice <br/>totalSalePrice改为totalSettlePrice<br/>totalPrice改为totalPayPrice<br/>机票火车票增加了totalTicketPrice<br/>酒店增加了totalDailyPrice |
| 1.9 | 陈玉石 | 2019-10-22 | 机票的创单接口中：<br/>出发航站楼和到达航站楼可空；<br/>出发时间和到达时间格式改为HH:mm<br/>酒店的创单接口，子订单数据结构中增加字段，<br/>num（房间数）酒店的订单详情接口，<br/>子订单数据结构中增加字段，num（房间数） |
| 2.0 | 陈玉石 | 2019年10月28日 | 1. 酒店的子订单中，增加一个子订单号，<br/>2.订单完成回调接口中，增加了一个字段finishType，<br/>用来标记是出票完成，还是订单完成。 <br/>3. 所有的创单和订单详情里都加上了qType,qParam两个参数，<br/>分别代表了店主佣金的配置方式和参数。<br/>4. 增加了结算公式<br/>5. 增加了佣金配置参数的说明 |
| 2.1 | 陈玉石 | 2019年10月28日 | 1、增加了统一床单接口（根据平台规范）<br/>2、修改了订单详情接口的统一入口，去掉了type；<br/>3、详情返回接口增加了字段busiType用来标识订单种类，<br/>增加了orderFinishTime用来返回订单的业务完成时间； |
| 2.2 | 陈玉石 | 2019年12月11日 | 裁剪文档 |
| 2.3 | 陈玉石 | 2020年2月24日 | 修改totalDiscountPrice的说明；平台创建订单接口、<br/>订单状态同步接口、获取订单详情接口增加字段channel |
| 2.4 | 范松灿 | 2020年02月26日 | 获取订单详情接口增加channel和type字段 |
| 2.5 | 陈玉石 | 2020年02月26日 | 订单状态同步增加已完成状态（syncType=11) |
| 2.6 | 陈玉石 | 2020年02月28日 | [创单](H5.md#平台创建订单接口)和[获取订单详情接口](H5.md#获取订单详情接口)增加参数 source ，用来判定订单的输入来源。 |





# gitbook
