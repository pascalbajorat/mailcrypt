mailcrypt
=========

MailCrypt - AntiSpam Email Encryption v.1.0.0


Include this in your HTML head or Footer
========================================

```html
<script type="text/javascript" src="js/jquery.js"></script>
<script type="text/javascript" src="js/mailcrypt.js"></script>
```

Start Decrypting Mail-Adresses
==============================

```html
<script type="text/javascript">
	$(document).ready(function(){
		$('a.mailcrypt').mailcrypt();
	});
</script>
```

Use this structure for your mails:
==================================

```html
<a href="kontakt.html" class="mailcrypt">info<span><span>∂</span></span>webdesign-podcast.de</a>
```

You can replace the ∂ sign with an @ image or another sign what ever you want.

Copyright (c) 2013 Pascal Bajorat
Dual licensed under the MIT and Gnu GPL version 3 licenses.



## [Main Demo](http://www.webdesign-podcast.de/wp-content/uploads/2011/06/mailcrypt/)

* [Documentation](https://github.com/pascalbajorat/mailcrypt/wiki)
* [Latest demos](http://www.webdesign-podcast.de/wp-content/uploads/2011/06/mailcrypt/)
* [Download](https://github.com/pascalbajorat/mailcrypt/zipball/master)
* [Author](https://www.pascal-bajorat.com/)