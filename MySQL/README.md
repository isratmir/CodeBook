#MySQL

###Query

#####Row number on select
```
sql
SET number = 0;
SELECT @number:=@number+1 AS Number, name, phone FROM `users`;
```