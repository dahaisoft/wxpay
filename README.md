# wxpay
微信企业付款
```php
$pay = new Wxpay\CompanyPay;
$pay->appid = '';
$pay->mchid = '';
$pay->key = '';
$pay->sslcert_path = '';
$pay->sslkey_path = '';
$pay->pay($openid, $trade_no, $money, $desc);
```