## 签约微信免密支付
查看 [详情](https://pay.weixin.qq.com/wiki/doc/api/pap.php?chapter=18_5&index=2).
```dart
   import 'package:fluwx_no_pay/fluwx_no_pay.dart' as fluwx;
   fluwx.autoDeDuct(
           appId: "",
           mchId: "",
           planId: "",
           contractCode: "",
           requestSerial: "",
           contractDisplayAccount: "",
           notifyUrl: "",
           version: "",
           sign: "",
           timestamp: "",
           returnApp: '3');
```