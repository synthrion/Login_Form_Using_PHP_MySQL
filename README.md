# Creating Login Form Using PHP and MySQL
Tutorial from Dave Hollingworth at https://www.youtube.com/watch?v=5L9UhOnuos0&t=2106s&ab_channel=DaveHollingworth
<br>
<br>
<br>
## Writing this because I have a bad memory. For future use only.

### Things to do before running:

1.) Download XAMPP ---> https://www.apachefriends.org/ <br>
2.) Go to XAMPP Control Panel <br>
3.) Turn ON Apache, and MySQL <br>
4.) Go to <u>localhost/phpmyadmin</u> or click Admin in XAMPP Control Panel <br>
5.) Build database as "login_db" <br>
6.) Create 4 tables as "user" <br>
  &emsp;1. <b>id</b> 
  <ul>
   <li>data type must be INT(11)</li>
   <li>A_I (AUTO_INCREMENT)</li>
   <li>keyname must be PRIMARY</li>
  </ul>  <br>
  &emsp;2. <b>name</b>  
  <ul>
   <li>data type must be varchar(128)<br></li>
  </ul>  
<br>
  &emsp;3. <b>email</b> 
  <ul>
   <li>data type must be varchar(255)</li>
  <li>keyname must be UNIQUE</li>
  </ul>  
<br>
  &emsp;4. <b>password_hash</b> (a) <br>
  
<ul>
   <li>data type must be varchar(255)</li>
  </ul>  
  ![image](https://user-images.githubusercontent.com/74046232/196758256-0928efb0-c2d6-4ff5-87a5-95e5957b9427.png)

