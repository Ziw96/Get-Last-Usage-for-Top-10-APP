# Get-Last-Usage-for-Top-10-APP
For Tecent WXG interview


--表A结构为：
CREATE TABLE user_visit_log(  
ds STRING COMMENT '日期 分区字段',  
user_id BIGINT COMMENT 'Uin',  
visit_time BIGINT COMMENT '访问时间戳 单位 s',  
scene BIGINT COMMENT '进入应用号场景 ',  
sessionid STRING COMMENT '单次访问会话 id',  
appid STRING COMMENT 'appid'  
) 
""" 
背景：每天一份当天访问应用的用户，用户数达到亿级别 
Q：用sql获取当天访问人数TOP10的小程序当天最后一个会话访问的用户、场景和会话id  
要求：放一份到github后，提供地址 
"""
