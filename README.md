'modernphp' Standard for PHP_CodeSniffer
===============================================

PEAR/Zendのコーディング規約をベースにしたモダンPHPのコード規約です。

インストールとセットアップ
----------

* [PHP_CodeSniffer](http://pear.php.net/PHP_CodeSniffer) を`pear install PHP_CodeSniffer` (要PHP_CodeSniffer 1.3以上)でインストールします。
* cd /path/to/PEAR/PHP/CodeSniffer/Standards
* git clone git@github.com:koriym/phpcs-modernphp.git modernphp
* phpcs set-config standard modernphp
* phpcs /path/to/your_project/src

Installation
------------

* Install [PHP_CodeSniffer](http://pear.php.net/PHP_CodeSniffer) with `pear install PHP_CodeSniffer` (PHP_CodeSniffer 1.3 or later is required).
* Checkout this repository as `BEAR` into the `PHP/CodeSniffer/Standards` directory.
* Use the coding standard with `phpcs --standard=modernphp`.
