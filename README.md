# wechat-pay-doc

微信支付


 oooO ↘┏━┓ ↙ Oooo 
 ( 踩)→┃你┃ ←(死 ) 
  \ ( →┃√┃ ← ) / 
　 \_)↗┗━┛ ↖(_/ 

坑

## 安全域名设置

支付那块安全域名设置

比如 你设置的 是 abc.com/wx/

你支付回调不能用 abc.com/wx/订单号/价格 这样的path方式

你只能使用 abc.com/wx/订单号?price=20 这样的querystring模式