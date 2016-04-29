####Change column name

```
rename_column :table, :old_column, :new_column
```

####Add reference column

```
add_reference :apps, :app_types, index: true
```