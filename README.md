php-timeclock
=============

Fork of [php timeclock 2.0RC2](http://en.sourceforge.jp/projects/sfnet_phptimeclock/releases/) and edited specifically for Asterisk integration


Summary of Changes:
===================

 * Force all numeric usernames
/functions/general.php  line 113 change:

`define('VALID_USER_NAME_REGEX', '^[a-z][a-z0-9]{1,31}$');`
to
`define('VALID_USER_NAME_REGEX', '^[0-9]{1,31}$');`
