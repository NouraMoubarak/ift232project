# ift232project
tbl_unicoursesCREATE TABLE `tbl_unicourses` (
  `crs_id` int(11) NOT NULL AUTO_INCREMENT,
  `crs_code` varchar(6) NOT NULL,
  `crs_name` varchar(30) NOT NULL,
  `crs_description` varchar(250) DEFAULT NULL,
  `crs_type` varchar(8) NOT NULL,
  `crs_nb_of_credit` int(11) NOT NULL DEFAULT '3',
  `crs_lab` varchar(7) NOT NULL DEFAULT 'not lab',
  PRIMARY KEY (`crs_id`)
) ENGINE=InnoDB AUTO_INCREMENT=2 DEFAULT CHARSET=utf8;
