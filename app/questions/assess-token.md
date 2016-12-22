###access_token过期问题

*  一个小时内重新获取token，不会生成新token，token过期时间变为这次token获取时间往后7200秒
*  若获取到新的token，旧token依然在原来的7200秒内过期
