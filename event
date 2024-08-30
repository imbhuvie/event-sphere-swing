/*
SQLyog Ultimate v8.82 
MySQL - 5.1.50-community : Database - event
*********************************************************************
*/

/*!40101 SET NAMES utf8 */;

/*!40101 SET SQL_MODE=''*/;

/*!40014 SET @OLD_UNIQUE_CHECKS=@@UNIQUE_CHECKS, UNIQUE_CHECKS=0 */;
/*!40014 SET @OLD_FOREIGN_KEY_CHECKS=@@FOREIGN_KEY_CHECKS, FOREIGN_KEY_CHECKS=0 */;
/*!40101 SET @OLD_SQL_MODE=@@SQL_MODE, SQL_MODE='NO_AUTO_VALUE_ON_ZERO' */;
/*!40111 SET @OLD_SQL_NOTES=@@SQL_NOTES, SQL_NOTES=0 */;
CREATE DATABASE /*!32312 IF NOT EXISTS*/`event` /*!40100 DEFAULT CHARACTER SET latin1 */;

USE `event`;

/*Table structure for table `booking` */

DROP TABLE IF EXISTS `booking`;

CREATE TABLE `booking` (
  `bid` bigint(10) DEFAULT NULL,
  `type` varchar(20) DEFAULT NULL,
  `place` varchar(20) DEFAULT NULL,
  `guest` varchar(10) DEFAULT NULL,
  `dt` varchar(15) DEFAULT NULL,
  `dj` varchar(5) DEFAULT NULL,
  `stage` varchar(5) DEFAULT NULL,
  `mike` varchar(5) DEFAULT NULL,
  `breakf` varchar(5) DEFAULT NULL,
  `lunch` varchar(5) DEFAULT NULL,
  `tea` varchar(5) DEFAULT NULL,
  `dinner` varchar(5) DEFAULT NULL,
  `vegtype` varchar(10) DEFAULT NULL,
  `foodtype` varchar(20) DEFAULT NULL,
  `light` varchar(20) DEFAULT NULL,
  `flower` varchar(20) DEFAULT NULL,
  `seat` varchar(20) DEFAULT NULL,
  `total` varchar(20) DEFAULT NULL,
  `status` varchar(20) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

/*Data for the table `booking` */

insert  into `booking`(`bid`,`type`,`place`,`guest`,`dt`,`dj`,`stage`,`mike`,`breakf`,`lunch`,`tea`,`dinner`,`vegtype`,`foodtype`,`light`,`flower`,`seat`,`total`,`status`) values (1310181910,'Item 1','Item 1','','','No','No','No','No','No','No','No','','Select-----','Item 1','Item 1','Item 1','','Seen'),(1310181931,'Marriage','Vinay Garden','200','','Yes','Yes','Yes','Yes','Yes','Yes','Yes','','Royal','Royal','Royal','Royal','258000.0','Pending');

/*Table structure for table `customer` */

DROP TABLE IF EXISTS `customer`;

CREATE TABLE `customer` (
  `uid` int(4) DEFAULT NULL,
  `name` varchar(25) DEFAULT NULL,
  `mob` varchar(15) DEFAULT NULL,
  `email` varchar(25) DEFAULT NULL,
  `gen` varchar(10) DEFAULT NULL,
  `city` varchar(20) DEFAULT NULL,
  `state` varchar(20) DEFAULT NULL,
  `country` varchar(20) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

/*Data for the table `customer` */

insert  into `customer`(`uid`,`name`,`mob`,`email`,`gen`,`city`,`state`,`country`) values (1234,'Inshaal','8986887','dvnnvkdvjn','Male','lko','skbd','sd ');

/*Table structure for table `employee` */

DROP TABLE IF EXISTS `employee`;

CREATE TABLE `employee` (
  `eid` int(4) DEFAULT NULL,
  `ename` varchar(20) DEFAULT NULL,
  `aadhar` varchar(20) DEFAULT NULL,
  `desig` varchar(20) DEFAULT NULL,
  `gen` varchar(10) DEFAULT NULL,
  `mob` varchar(15) DEFAULT NULL,
  `email` varchar(20) DEFAULT NULL,
  `doj` varchar(15) DEFAULT NULL,
  `addr` varchar(60) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

/*Data for the table `employee` */

insert  into `employee`(`eid`,`ename`,`aadhar`,`desig`,`gen`,`mob`,`email`,`doj`,`addr`) values (1,'Karuna','111111111','ksjdnvk','Male','8768768','mcbvjhc','12-12-1212','jhjhvnvj');

/*Table structure for table `login` */

DROP TABLE IF EXISTS `login`;

CREATE TABLE `login` (
  `username` varchar(20) DEFAULT NULL,
  `password` varchar(20) DEFAULT NULL,
  `usertype` varchar(20) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

/*Data for the table `login` */

insert  into `login`(`username`,`password`,`usertype`) values ('admin','admin','Admin'),('Ankit','1234567','Employee'),('Karuna','123456','Employee');

/*Table structure for table `venue` */

DROP TABLE IF EXISTS `venue`;

CREATE TABLE `venue` (
  `venue` varchar(30) DEFAULT NULL,
  `addr` varchar(60) DEFAULT NULL,
  `phone` varchar(15) DEFAULT NULL,
  `capacity` varchar(10) DEFAULT NULL,
  `prefer` varchar(25) DEFAULT NULL,
  `rupees` varchar(10) DEFAULT NULL,
  `image` longblob
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

/*Data for the table `venue` */

insert  into `venue`(`venue`,`addr`,`phone`,`capacity`,`prefer`,`rupees`,`image`) values ('Vinay Garden','sdlknls','11111111111','120','Marriage','90000','âPNG\r\n\Z\n\0\0\0\rIHDR\0\0\0\0\0\0\0\0\0ƒÈÖc\0\0\0bKGD\0ˇ\0ˇ\0ˇ†Ωßì\0\0ÛIDATH\r›VMhA~3ù$M†Ωm°bo‚±‡œI°E¸CãäO›,EÉ¢¢gÈ•`•M6SQ{hUÒ&®ı†öÉJë‚I<¯≠H≠!õŸ}~SH1Õö<ﬁ∞oæyÛ}ÛÊÕÏÜË˘â’â§›Ù6_¯W„Å}A‚*˛(pÏ/∞Lƒ—ŒafûBÃî√3ÿò:òX Êò≠lT°\ZNaÚ™KR?°‡”dJßŒ\"£˚BIV\ZXéu–Sƒe!4ñ‘…^¯ÅVè∏ŸJÏsV∞»T™KD—ÀöøA§MBu,Â¶∂¬/1U“´¢Éz‹A—c≈)8,Ì¿)6\0õA[±öE¨êuaÖN≤ê‹eD‡ñY]€U∆V¯\'\"5oWq—£<⁄Íyﬁ·ãù,òP¸Õ<—–#zºbLÕôÚ`u∏ÈiÔ3à«!`R\\ûz·ùSpvòæi5â8Ïƒb:ˆÖ>Å	Ôe≈≠‰—&‹óÛ nˆoÇ£kºÒ\r`Úv[;éünQ-”T†n_˙ÕVÿ\ZÇ‡åœawìúlØ:LZr„vÿv@FK¥¬≈ÃH!èõæ-ÏÔ“ó\'‡G•ñâ™/=π[B\rnõê5¢AóUÜ3çã¥»}¢o/—◊àÌ™:0m4ÑJ©ÛÖ˘ﬁºŒÁ–~5J¿œE\nëπÂæ≥xvTù	D~æBnﬁm¬+‰=à∞ZÖg¯åO#ÀeQˆπÿR’\"¯jfAH\r≤°EøÖïfÕ!ÉÑàá‚óÅ—EH”n¯3E@Ù{™dV{}òá\'˚EˇWSÉG>[Œ¿LÎU<€Ä•úKªÈNEª\\’,⁄|Úª%…è8i\'ë—€b» .iTGØ`ë◊Ä=±îu®Lk≤=rP≤ºá‡&‘‰%é˘‘àïwA`)OygêÈØöE@BÿÆ6•’%ds6ßŒ¸Òx¡d–ƒòˆ8y3æã\Z–\0\0\0\0IENDÆB`Ç');

/*!40101 SET SQL_MODE=@OLD_SQL_MODE */;
/*!40014 SET FOREIGN_KEY_CHECKS=@OLD_FOREIGN_KEY_CHECKS */;
/*!40014 SET UNIQUE_CHECKS=@OLD_UNIQUE_CHECKS */;
/*!40111 SET SQL_NOTES=@OLD_SQL_NOTES */;
