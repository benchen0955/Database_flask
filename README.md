# Database_flask
CREATE SCHEMA `root_schema` ;創建SCHEMA名稱root_schema
CREATE TABLE `test`.`student` (
  `id` INT NOT NULL,
  `name` VARCHAR(32) NULL,
  PRIMARY KEY (`id`));
在test 建表(table)student('id' 數值not null,'name'字串(32長度) null),id 主鍵 

insert into test.student (id,name) values (1,"ben");id 是prime
delete from test.student where id=2;
SELECT * FROM test.student where id=2;
update test.student set name="joy" where id=1;
SELECT * FROM test.student order by id desc;reverise id 
SELECT * FROM test.student order by id asc;forward id
