CREATE DATABASE student;
DROP TABLE IF EXISTS `admin`;
CREATE TABLE `admin` (
 `id` int(11) NOT NULL AUTO_INCREMENT,
 `name` varchar(20) NOT NULL,
 `username` varchar(20) NOT NULL,
 `password` varchar(20) NOT NULL,
 PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=2 DEFAULT CHARSET=utf8;
 
LOCK TABLES `admin` WRITE;
INSERT INTO `admin` VALUES (1,'admin','admin','admin');
UNLOCK TABLES;
 
DROP TABLE IF EXISTS `student`;
CREATE TABLE `student` (
 `id` int(11) NOT NULL AUTO_INCREMENT,
 `name` varchar(20) NOT NULL,
 `sno` varchar(20) NOT NULL,
 `department` varchar(20) NOT NULL,
 `hometown` varchar(20) NOT NULL,
 `mark` varchar(20) NOT NULL,
 `email` varchar(20) NOT NULL,
 `tel` varchar(20) NOT NULL,
 `sex` varchar(20) NOT NULL,
 PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=22 DEFAULT CHARSET=utf8;
 
LOCK TABLES `student` WRITE;
UNLOCK TABLES;
