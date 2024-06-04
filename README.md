# 线上的招标比价系统
1、项目介绍<br />
  系统用于线上比价功能，系统符合审计的相关要求。线上分析供应商报价、报价内容拆解等。<br />
2、系统基础信息<br />
(1)角色管理：名称、权限、状态。<br />
(2)账号信息管理：姓名、部门、员工编号、登陆名、密码、最后登陆时间、是否域用户、域用户名。<br />
(3)账号密码安全策略：密码长度、历史保存几次、密码有效时间、长期不使用天数锁定。<br />
(4)职员信息管理：姓名、部门、员工编号、电话，第三方系统比对姓名、员工编号。<br />
(5)部门管理：部门管理、部门对应的仓库管理（该部门对该仓库的查看报价，用于工厂或部门间的数据逻辑隔离）。<br />
(6)供应商管理：名称、编码、联系人、分类等级、安全等级、分类配置（支持多选、支持自定义内容），供应商审核（自定义需要审核的文件，供应商通过审核后，登录系统后才显示报价等业务菜单）<br />
3、比价/招标功能<br />
  (1)采购申请编号、采购明细。<br />
  (2)采购内容发布：采购员选择要发布的采购单，并选择相应的供应商，设置比价的时间、分别给供应商发送邮件。<br />
  (3)比价过程（类似招标），实时报价（可以设置开标前价格是否保密）、比价时分析价格、分析供应商审核文件是否有效、供应商IP地址是否重复、供应商终端设备ID、支持临时分包、分标段，支持多轮次报价<br />
  (4)价格确认供应商线上签字报价、模板自定义、且记录模板版本。<br />
4、当前流程：<br />
  (1)需求人员在9.1增加其需求的内容,注意添加明细项.<br />
  (2)采购人员在9.3招投标发布 /9.4询价发布根据需求发布给对应的供应商.根据供应商在10.10配置进行邮件发送,若配置有问题邮件中会有提醒. 系统中若不存在该供应商,采购人员在5.1进行添加维护,维护保存后,再次编辑在登陆帐号标签页内添加默认帐号,帐号会自动发送邮件给供应商,若维护帐号邮件错误,请联系管理员.<br />
  (3)供应商收到采购需求的邮件（包括内容与招标时间）,请提前在系统中维护相应价格,在10.1/10.2/10.6均可（报价时自动计算选项若发现与实际不符请取消其钩选）,且一处变更其它处也随之变化,在邮件提醒的时间在安静有网络通信的场所进行线上招标.若采购人员通知现场招标,请相关人员自行配置电脑到现场,电脑\手机等电子设 
     备最好配有防窥膜等防止信息泄露的配件或设施.<br />
  (4)线上竞标时根据采购要求进行报价：1、不需要明细也随之更新,可以在10.6进行快速报价,带的单元格可以直接编辑,编辑后鼠标点下空白的地方会提标修改成功. 修改完成后选择提交至轮次.<br />
  (5)采购人员经过多报价后,确认数据无误,在9.7询价/邀标->定标->确认报价,供应商在10.7进行签字确认.<br />


使用文档用于商业目的，请联系作者购买。<br />
软件开发中源码：https://github.com/wanglei0803/EAM<br />
Vx：kaixinsanshi<br />

  
    
    
    
