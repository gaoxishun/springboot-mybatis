# springboot-mybatis
A simple demo with SpringBoot and Mybatis

-- ----------------------------
-- Table structure for user
-- ----------------------------
DROP TABLE IF EXISTS `user`;
CREATE TABLE `user` (
  `id` int(11) NOT NULL,
  `name` varchar(255) DEFAULT NULL,
  `age` int(11) DEFAULT NULL,
  `password` varchar(255) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
-- ----------------------------
-- Records of user
-- ----------------------------
INSERT INTO `user` VALUES ('1', '7player', '18', '123456');


http://localhost:8080/hello?name=7player

http://localhost:8080/getUserInfo

Restful（使用了swagger）：

http://localhost:8080/swagger/index.html
