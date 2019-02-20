# sql-where-in-php-array
Делаем sql запрос с фильтром из php массива WHERE UID  IN join

$sqlUpdate = array(1, 2, 3);
 $strSql = "UPDATE `a_importer` SET `UPDATE` = 'N' WHERE UID  IN ('" . join('\',\'', $sqlUpdate) . "')";
