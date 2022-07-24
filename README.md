It uses PHP and JavaScript to achieve multiple files upload to Mysql


SQL script to create table for saving:
CREATE TABLE `user` (
  `id` int(11) NOT NULL,
  `images` varchar(255) NOT NULL,
  `date_time` datetime NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8;