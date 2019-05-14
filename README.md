# mysql-go-demo
A simple MySQL operation demo in Go

This example shows how to operate on MySQL database based  on `database/sql` interface standards.

It creats SQL as follows:

    CREATE TABLE `userinfo` (
      `uid` INT(10) NOT NULL AUTO_INCREMENT,
      `username` VARCHAR(64) NULL DEFAULT NULL,
      `department` VARCHAR(64) NULL DEFAULT NULL,
      `created` DATE NULL DEFAULT NULL,
      PRIMARY KEY (`uid`)
	);