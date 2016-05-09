#MySQL

###Query

#####Row number on select
```sql
SET number = 0;
SELECT @number:=@number+1 AS Number, name, phone FROM `users`;
```

#####Update with subselec from same table
```sql
UPDATE test AS a JOIN test AS b ON a.id = b.id SET a.name = 'New Name' WHERE a.id = 104;
```

#####Subquery in insert operation
```sql
INSERT INTO table(column1, column2, column3) VALUES('value1', (SELECT id FROM table AS id_value where id='SomeID'),'value3');
```