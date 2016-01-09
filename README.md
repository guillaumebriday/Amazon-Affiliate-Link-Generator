# Amazon Link Generator

This is a website to generate Amazon links with your tag inside if you are an amazon partner. [Bitly](https://bitly.com/) API is used to shorten the link.
It's built in vanilla JavaScript prevents the importation of jquery (or equivalent) and improves performance.
PHP is used as server side langage to keep your bitly access token private.


## Installation

You will need to change the variables "tag" and "access_token" with your personal information as follows :

In index.html

```javascript
var tag = "your_amazon_personal_tag";
```

In bitly.php

```php
$access_token = "your_bitly_personal_access_token";
```

## Improvements

Feel free to request suggestions or bug corrections to improve the project.
