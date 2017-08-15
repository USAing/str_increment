# str_increment
---
String Increment Class


#### Travis CI

[![Travis-ci](https://api.travis-ci.org/yakeing/str_increment.svg)](https://travis-ci.org/yakeing/str_increment)

#### Packagist

[![Version](http://img.shields.io/packagist/v/yakeing/str_increment.svg)](https://packagist.org/packages/yakeing/str_increment)
[![Downloads](http://img.shields.io/packagist/dt/yakeing/str_increment.svg)](https://packagist.org/packages/yakeing/str_increment)

#### Github

[![Downloads](https://img.shields.io/github/downloads/yakeing/str_increment/total.svg)](https://github.com/yakeing/str_increment)
[![Size](https://img.shields.io/github/size/yakeing/str_increment/src/str_increment/StrIncrement.php.svg)](https://github.com/yakeing/str_increment/tree/master/src/str_increment)
[![tag](https://img.shields.io/github/tag/yakeing/str_increment.svg)](https://github.com/yakeing/str_increment)
[![Language](https://oauth.applinzi.com/SvgLabel/4D4D4D/Language/F66000/PHP/image.svg)](https://github.com/yakeing/str_increment)
[![License](https://oauth.applinzi.com/SvgLabel/4D4D4D/License/007EC6/MPL-2.0/image.svg)](https://github.com/yakeing/str_increment)

#### Old Version

[![Version](https://oauth.applinzi.com/SvgLabel/4D4D4D/Version/007ec6/1.0/image.svg)](https://github.com/yakeing/str_increment/tree/master/version1.0)
[![Size](https://img.shields.io/github/size/yakeing/str_increment/version1.0/StrIncrement.php.svg)](https://github.com/yakeing/str_increment/tree/master/version1.0)

[![Version](https://oauth.applinzi.com/SvgLabel/4D4D4D/Version/007ec6/1.1/image.svg)](https://github.com/yakeing/str_increment/tree/master/version1.1)
[![Size](https://img.shields.io/github/size/yakeing/str_increment/version1.1/StrIncrement.php.svg)](https://github.com/yakeing/str_increment/tree/master/version1.1)
` Singleton pattern `

[![Version](https://oauth.applinzi.com/SvgLabel/4D4D4D/Version/007ec6/2.0/image.svg)](https://github.com/yakeing/str_increment/tree/master/version2.0)
[![Size](https://img.shields.io/github/size/yakeing/str_increment/version2.0/StrIncrement.php.svg)](https://github.com/yakeing/str_increment/tree/master/version2.0)

BY: [yakeing](http://weibo.com/yakeing)

str_increment init / Set up
---

#### 16Hex ( Must be lowercase )
```php
    $str = '0fff';
    $ret = StrIncrement::NewStr($str, 16);
    var_dump('1000' == $ret);
```

#### 10Hex ( Decimalist )
```php
    //string
    $str = '1999';
    $ret = StrIncrement::NewStr($str, 10);
    var_dump('2000' == $ret);

      //integer
    $int = 100;
    $ret = StrIncrement::NewStr($int, 10);
    var_dump('101' == $ret);
```

#### Letters
```php
    $str = 'ABzZ';
    $ret = StrIncrement::NewStr($str, 'letters');
    var_dump('ABAa' == $ret);
```

#### Lowercase
```php
    $str = 'zxc';
    $ret = StrIncrement::NewStr($str, 'lowercase');
    var_dump('zxd' == $ret);
```

#### Capital
```php
    $str = 'ABZ';
    $ret = StrIncrement::NewStr($str, 'capital');
    var_dump('ACA' == $ret);
```

#### str_increment usage scenario

- [x] URL
```
  https://github.com/fTg5A

  https://github.com/0EaG7
```

- [x] USER ID
<table>
    <tr><th>USER</th><th>UID</th></tr>
    <tr><td>John</td><td>F8aJ0e</td></tr>
    <tr><td>Kim</td><td>fWd0fJ</td></tr>
    <tr><td>Mary</td><td>F8qWc5</td></tr>
</table>

Donate
---
Your donation makes CODE better.

 Bitcoin (比特币赞助)

 1Ff2hTfr4EioWv2ZDLKTedUiF9wBBVYSbU

 ![Bitcoin](https://oauth.applinzi.com/QR/230/bitcoin%3a1Ff2hTfr4EioWv2ZDLKTedUiF9wBBVYSbU/Bitcoin.png)

 WeChat (微信赞助)

 ![WeChat](https://oauth.applinzi.com/QR/230/wxp%3a%7C%7Cf2f0SOGAUjQ1ALzigoyN7nW8tK68D2oeU3YO/WeChat.png)

 Alipay (支付宝赞助)

 ![Alipay](https://oauth.applinzi.com/QR/230/HTTPS%3a%7C%7CQR.ALIPAY.COM%7CTSX082709YGHVXYUQCWKD6/Alipay.png)

