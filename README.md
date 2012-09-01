httpcurl-php
============

Http File transfer with PHP CURL


Transfer remote files with your php script through http.

Features
------------

- Download remote file 
- Read remote file content (ex: html, xml, etc.)
- Upload file to remote host (emulate form upload)
- Transfer remote file to remote host 


Basic usage
------------

<<<<<<< HEAD
Ini 

include "httpfiles.php";
$httpf= new Httpfiles();

Download remote file 

	<code>$httpf->get_file("http://www.host.com/example.jpg","./downloads/example.jpg");</code>
=======
include("httpfiles.php");
$httpf= new Httpfiles;

Download remote file 

$httpf->get_file("http://www.host.com/example.jpg","./downloads/example.jpg");
>>>>>>> 42f45dd42bb9829d8db43df491d4f412f70465f2


Read remote file

<<<<<<< HEAD
	$content= $httpf->read_file("http://www.host.com/index.html")
	print_r($content);
=======
$content= $httpf->read_file("http://www.host.com/index.html")
print_r($content);
>>>>>>> 42f45dd42bb9829d8db43df491d4f412f70465f2


Upload file to remote host

<<<<<<< HEAD
	$httpf->send_file("./dowmloads/example.jpg","http://www.host.com/upload.php","userfile");

	// userfile is the field of the upload file (like in html: <input type="file" name="userfile"/>)
=======
$httpf->send_file("./dowmloads/example.jpg","http://www.host.com/upload.php","userfile");

// userfile is the field of the upload file (like in html: <input type="file" name="userfile"/>)
>>>>>>> 42f45dd42bb9829d8db43df491d4f412f70465f2


Transfer remote file to remote host

<<<<<<< HEAD
	$http->transfer_file("http://www.host1.com/example.jpg","http://www.host2.com/upload.php","userfile","example.jpg");
=======
$http->transfer_file("http://www.host1.com/example.jpg","http://www.host2.com/upload.php","userfile","example.jpg");
>>>>>>> 42f45dd42bb9829d8db43df491d4f412f70465f2
