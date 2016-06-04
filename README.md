# tutajuablogs
TutajuaBlogs is an Open Source blog tool and publishing platform powered by PHP and MySQL. It has a Content Management System (CMS) for each individual blog within the TutajuaBlogs and an overall admin CMS for controlling all the blogs. TutajuaBlogs is built on the CodeIgniter Framework

2016 TutajuaBlogs 

NOTICE OF LICENSE

This source file is subject to the The MIT License (MIT)
that is bundled with this package in the file LICENSE.txt.
It is also available through the world-wide-web at this URL:
https://opensource.org/licenses/MIT
If you did not receive a copy of the license and are unable to
obtain it through the world-wide-web, please send an email
to baberuka@gmail.com so we can send you a copy immediately.

DISCLAIMER

Do not edit or add to this file if you wish to upgrade TutajuaBlogs to newer
versions in the future. If you wish to customize TutajuaBlogs for your
needs please refer to https://sourceforge.net/projects/tutajaublogs/forums/forum/1840749 for more information.

@author Solomon Bareebe <baberuka@gmail.com>
@copyright 2016 TutajuaBlogs
@license  https://opensource.org/licenses/MIT  The MIT License (MIT)

NAME: TutajuaBlogs 2.0
VERSION: 0.1

PREPARATION
===========

To install TutajuaBlogs, you need a remote web server or on your computer (MAMP), with access to a database like MySQL.
You'll need access to phpMyAdmin to create a database and to indicate the information in the database in the installer.

INSTALLATION
============

1. Unzip tutajuablogs.zip
2. open the folder application/config 
 	2.1  open the file database.php with a text editor such as notepad
 	2.2  The contents of database.php should be as follows
		<?php
		$db['default'] = array(
			'dsn'	=> '',
			'hostname' => 'localhost',
			'username' => 'root',
			'password' => 'admin',
			'database' => 'tutajuablogs',
			'dbdriver' => 'mysqli',
			'dbprefix' => '',
			'pconnect' => FALSE,
			'db_debug' => (ENVIRONMENT !== 'production'),
			'cache_on' => FALSE,
			'cachedir' => '',
			'char_set' => 'utf8',
			'dbcollat' => 'utf8_general_ci',
			'swap_pre' => '',
			'encrypt' => FALSE,
			'compress' => FALSE,
			'stricton' => FALSE,
			'failover' => array(),
			'save_queries' => TRUE
		);		
		
		?>
 	2.3  replace the database tutajuablogs with your preferred database
 	2.4  replace the database admin user root with your preferred database administrator
 	2.5  replace the password admin with your preferred database password
3. Open tutajuablogs.sql in the root folder of the application
 	4.1  Change the database name by editing the line below
	Database: `tutajuablogs`
	4.2  Import the database using phpmyadmin by uploading the file tutajuablogs.sql
 	4.3  Delete tutajuablogs.sql after uploading the database
4. Upload the contents to your website root folder
5. Click on your website URL. Your website should be up and running if you entered the database details above correctly
6. Click on http://your-website-url/login/index and login using the username and password combination below to login as the OVERALL ADMINISTRATOR
		Admin Login:	solomon@tutajuablogs.tutajua.net
		Admin Password:	solomon@2016
 	6.1  NB: Change the username and passwords, edit, create or delete blogs
7. To login as a Blog user Click on Login or http://your-website-url/login/index and use any of the username and password combinations below
 	7.1  Solomon Bareebe's Blog (logs you into Solomon Bareebe's Blog using the above login details.)
    	NB: Solomon is the Super Admin and he can therefore accesss all blogs
 	7.2  Paul Osul's Blog (logs you into Paul Osul's Blog)
		
		User Login:		paul@tutajuablogs.tutajua.net
		User Password:	paul@2016

 	7.3  change the username and passwords, edit or delete the blog 

If you have any PHP error, perhaps you don't have PHP5 or you need to activate it on your web host.

If you find any errors, please feel free to email me :-)

There are always solutions for your issues ;-)


Thanks for downloading and using TutajuaBlogs!

==================================================================================================================================
=     											Solomon Bareebe    																 =
=   									www.TutajuaBlogs.bareebe.com   															 =
==================================================================================================================================
