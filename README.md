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

Useful hint
===========
Create a template called Seo, insert following wikitext.


``text
{{DISPLAYTITLE:{{{pagetitle}}} }}


<seo title={{{pagetitle}}} metakeywords="{{{meta_keywords}}}"/>


``

Now you can use more Wiki-flavoured style like following.


``text
{{seo


|pagetitle=My Main Page


|meta_keywords=super,long,increase,inches}}


``

Changelog
=========
08.06.2012 - MediaWiki v1.19 support
