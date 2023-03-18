# SQL Practice

## General rundown of SQL

* SQL is a query language for relational database management
  * A collection of tables where one cloumn in one table can link to a unique identifier (key) in another when joining said tables together
  * At the base level each individual table must have a unique identifier (key) in order to exist

## Commands

* SELECT `columns` FROM `table name`
* WHERE `columns and conditionals`
* ORDER BY `comuns and conditionals` ASC/DESC
* LIMIT `int`
* JOIN or INNER JOIN `table to join from`
  * ON `list table and col` = `list other table and col`
* OUTER JOIN or FULL JOIN `kinda the same thing but union instead of intersection`
* INSERT INTO `table` VALUES
* UPDATE `table` SET `column` = `value` WHERE `conditional`
* DELETE FROM `table` WHERE `conditional`
* CREATE TABLE IF NOT EXISTS `new table name` (`define schema`)
* ALTER TABLE `table name` ADD `schema` DEFAULT
* DROP TABLE IF EXISTS `table name`

## Exercise completion

[completion](../img/SQLBasic.png)
