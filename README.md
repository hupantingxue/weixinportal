开源的第三方微信开发者账号管理平台
=========================
开通账号流程  
1.admin后台开通账号，并新建app_item，并绑定。App内的处理事件字段，增加标示为，无匹配回复和关注的两个空事件  
2.客户账号登陆http://mp.weixin.qq.com/,填写url (token,app_item.id)，token验证得到appid, app_secrect, 填入app_item中  
3.用刚开通的账号重新登录/yimi-admin/  

=========================
Required Software:
1. mysql;
2. memcached;
