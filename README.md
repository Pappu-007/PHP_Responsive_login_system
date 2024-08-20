# PHP_Responsive_login_system

# PHP_keep_note-webapp-


<h2>The sql commands you have to run on your database:</h2>

<code>
CREATE DATABASE users;
USE users;

CREATE TABLE users (
    sno INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(15) NOT NULL,
    password VARCHAR(15) NOT NULL,
    dt DATETIME
);
</code>


