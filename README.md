**Abandoned!** See https://github.com/kasperhartwich/php-smssender

cpsms
=====

Use this to send a sms via danish sms-provider CPSMS. http://www.cpsms.dk

Example
-------

``` php
$recipient = '87654321';
$sender = 'cpsms for php';
$cpsms = new CPSMS('myUsername', 'myPassword'); 
$cpsms->send("Here come the sun.", $recipient, $sender);
```
