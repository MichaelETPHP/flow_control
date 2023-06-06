The main task of Flow Control component is to take the input Mule event and route it to one or more separate sequences of components.
It is basically routing the input Mule event to other sequence(s) of components
It is also called as Routers
most used routers under Flow Control component are:
Choice
Scatter-Gather
First Successful


Database TB

CREATE TABLE `data_tb_1` (
	`id` INT(11) NOT NULL AUTO_INCREMENT,
	`name` VARCHAR(50) NULL DEFAULT NULL COLLATE 'latin1_swedish_ci',
	`phone` VARCHAR(50) NULL DEFAULT NULL COLLATE 'latin1_swedish_ci',
	PRIMARY KEY (`id`) USING BTREE
)
COLLATE='latin1_swedish_ci'
ENGINE=InnoDB
AUTO_INCREMENT=11
;
