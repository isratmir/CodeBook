####Change column name

```
rename_column :table, :old_column, :new_column
```

####Add reference column

```
add_reference :apps, :app_types, index: true
```

####Migrate from file

```
json = ActiveSupport::JSON.decode(File.read('db/seeds/countries.json'))

json.each do |a|
  Country.create!(a['country'], without_protection: true)
end
```
