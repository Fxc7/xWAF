# xWAF
Free Web Application Firewall, Open-Source.

# Features

- [x] XSS Vulns Fixed.
- [x] SQL Inyections Fixed.
- [x] CSRF Easy to use, and validation.
- [x] Lightweight.
- [x] Cloudflare and BlazingFast Support.

# Sample Usage
```php
// Before of all your CODE.
require('xwaf.php');
$xWAF = new xWAF();
$xWAF->start();
// Your code below.
```
# Advanced Usage
```php
// Before of all your CODE.
require('xwaf.php');
$xWAF = new xWAF();
// Cloudflare Option [Optional]
$xWAF->useCloudflare();
// useBlazingfast Option [Optional]
$xWAF->useCloudflare();

// Check separated types.
$xWAF->checkGET();
$xWAF->checkPOST();
$xWAF->checkCOOKIE();
// Your code below.
```

# Requirements

- [x] PHP5.x+
- [x] Brain