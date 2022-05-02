9 Channel - A lightweight and full featured PHP imageboard.
========================================================

**9Chan has next to no active development<!--, however you can still pay for support. Basic support costs $40/hr, and is only payable in BTC. New features depend on what you want. Email COPYPASTE &lt;AT&gt; KITTENS &lt;DOT&gt; PH if you're interested&mdash;9chan forks such as OpenIB are included in this offer-->.**

About
------------
9chan is a free light-weight, fast, highly configurable and user-friendly
imageboard software package. It is written in PHP and has few dependencies.

*Security problems can be reported to the development team.*
	
While there is currently no active development besides fixing security problems, we don't exclude the possibility to refactor the code in order to meet today's standards and continue our work from the point where [@czaks](https://github.com/czaks) retired in 2017.
Before this milestone is achieved though, we strongly urge you to consider other imageboard packages. It is the opinion of the 9chan development team that no new 9chan imageboards should be deployed at the moment, and other imageboard packages used instead.


History
------------
9chan is a fork of (now defunc'd) [Tinyboard](http://github.com/savetheinternet/Tinyboard),
a great imageboard package, actively building on it and adding a lot of features and other
improvements. And [ViChan](https://github.com/vichan-devel/vichan)

### Maintainer timeline
1. [@h00j](https://github.com/h00j) (2021 - present)
2. [@ctrlcctrlv](https://github.com/ctrlcctrlv) (2017 - 2021)
3. [@czaks](https://github.com/czaks) (2014 - 2017) (The author of vichan fork)
4. [@savetheinternet](https://github.com/savetheinternet) (2010 - 2014) (The creator of Tinyboard)

Requirements
------------
1.	PHP >= 5.4 (we still try to keep compatibility with php 5.3 as much as possible)
        PHP 7.0 is explicitly supported. PHP 7.2 works as well, but may cause as yet unreported bugs.
2.	MySQL/MariaDB server
3.	[mbstring](http://www.php.net/manual/en/mbstring.installation.php) 
4.	[PHP GD](http://www.php.net/manual/en/intro.image.php)
5.	[PHP PDO](http://www.php.net/manual/en/intro.pdo.php)
6.	A Unix-like OS, preferrably FreeBSD or Linux

We try to make sure 9chan is compatible with all major web servers. 9chan does not include an Apache ```.htaccess``` file nor does it need one.

### Recommended
1.	MySQL/MariaDB server >= 5.5.3
2.	ImageMagick (command-line ImageMagick or GraphicsMagick preferred).
3.	[APC (Alternative PHP Cache)](http://php.net/manual/en/book.apc.php),
	[XCache](http://xcache.lighttpd.net/) or
	[Memcached](http://www.php.net/manual/en/intro.memcached.php)


License
--------
See [LICENSE.md](http://github.com/vichan-devel/vichan/blob/master/LICENSE.md).