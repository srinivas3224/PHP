# PHP
PHP INSTALLATION IN UBUNTU


 Step1:

	sudo apt-get update

  step2:Copy/Paste the following line of code into Terminal and then press enter:

	sudo apt-get install apache2


  step3:Copy/Paste the following line of code into Terminal and then press enter:

	sudo apt-get install php5 libapache2-mod-php5


  step4:
  
  sudo /etc/init.d/apache2 restart

  step5:give permissions to folder

  sudo chmod -R 777 /var/www

  step 6:Testing


1:

cteate /var/www/html/abc.php  file

inside it place

<?php phpinfo(); ?>

save it

2:
cteate /var/www/html/abc1.php  file



<?php 

$a=10;
$b=25;
$c=$a+$b;
echo "welcome to php".$c;
 ?>

 save it




  step 7:


  in browser type

  http://localhost/abc.php

  http://localhost/abc1.php
