# web_avanzada

  Nombre carpeta: phpcrudajax
  
  Nombre BD: playersdb
  
  Insertar tabla:
  ```sh
  CREATE TABLE `players` (
   `id` int(11) NOT NULL AUTO_INCREMENT,
   `pname` varchar(50) NOT NULL,
   `email` varchar(100) NOT NULL,
   `phone` varchar(15) NOT NULL,
   `photo` varchar(100) NOT NULL,
   `status` enum('1','0') NOT NULL DEFAULT '1',
   PRIMARY KEY (`id`)
  ) ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=utf8
  ```
