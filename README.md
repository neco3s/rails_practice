# railsの練習

`git clone`


### 学んだ内容

- テーブル、フィールド(カラム,列)、レコード(ロウ,行)
- show databases,create database mydb,drop database mydb,select database(),select user(),drop user,use mydb,create table mytable (id int),show tables,desc mytable,drop table mytable,insert into mytable (id,name,age) values (1, 'neco3',23),select カラム from テーブル where 条件式,where カラム like '%hoge%',order by asc | desc,limit 3,UPDATE mytable SET age=30 WHERE id=2,delete from mytable where id = 1,
- mysqlコマンドは大文字、小文字、どっちでもいい、最近は小文字の印象らしい
- rootユーザではなく作業用ユーザを使って作業を行う(create user),権限を付与する(grant)
- 整数->int,少数->double,255文字まで->varchar,それ以外の文字->TEXT,date,time,datatime
- auto_increment(mysqlが自動的に連番を振る), not null(nullを許可しない), PRIMARY KEY(主キー,nullではない、重複しない値になる事が保証される,テーブルにつき１カラムだけ)
- エイリアス(別名),ascending(昇順1,2,3),descending(降順3,2,1)
- UPDATE,SET,WHEREとかは大文字じゃないと動かなかった(version8.0),deleteは小文字でも動いた

### 参考にした動画

<https://www.udemy.com/course/web-application-development/learn/lecture/33061384#overview>
