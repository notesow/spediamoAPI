# SpediamoAPI
Spediamo.it PHP API (shipping automation) | Php Library Model (Unofficial)

> Small PHP library for use [Spediamo.it](https://spediamo.it/).

[![Latest Stable Version](http://poser.pugx.org/notesow/spediamoapi/v)](https://packagist.org/packages/notesow/spediamoapi)
[![Latest Unstable Version](http://poser.pugx.org/notesow/spediamoapi/v/unstable)](https://packagist.org/packages/notesow/spediamoapi)
[![License](http://poser.pugx.org/notesow/spediamoapi/license)](https://packagist.org/packages/notesow/spediamoapi)

| PHP Version | Status | Require  | version |
|-------------|--------|----------|---------|
| PHP >=7.4   | @Beta  | Composer | 2.7.1   |

### 🐱‍🚀 Install Library:

` composer require notesow/spediamoapi`

### 💎 Register your [account](https://spediamo.it/app/v1#/registrati).

Manage all your orders at the same time and in one place!
Start enjoying Spediamo.it completely free!

#### 🐱‍🏍 Start SpediamoAPI Object:
```php
require_once "../autoloader.php";
new SpediamoAPI\SpediamoAPI('YOUR_API_KEY');
```