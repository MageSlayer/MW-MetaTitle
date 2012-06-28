MW-MetaTitle
============

An unofficial fork of [Add HTML Meta and Title](http://www.mediawiki.org/wiki/Extension:Add_HTML_Meta_and_Title official page) extension for MediaWiki.

Usage
=====
Copy Add_HTML_Meta_and_Title.php into 'extensions' directory.
Add following into your LocalSettings.php

```php
$wgSitename = "My Wiki";  
$wgAllowDisplayTitle = true;  
$wgRestrictDisplayTitle = false;  
require_once('extensions/Add_HTML_Meta_and_Title.php');  
```

Changelog
=========
08.06.2012 - MediaWiki v1.19 support
