# CodeBook
Code use cases

 * [regular expression](RegExp/README.md)
 * [Ruby On Rails](RubyOnRails/README.md)
 * [Ruby](Ruby/README.md)
 * [PHP](PHP/README.md)
 * [MySQL](MySQL/README.md)
 * [JavaScript](JavaScript/README.md)
 * [CSS](CSS/README.md)
 * [Python] (Python/README.md)
 * [Symfony] (Symfony/README.md)

 ## BASH
 ### Path variables

Incorrect 
```sh
 PROJECT_DIR = "/home/user/public_html/project";
```

 Correct 
```sh
 PROJECT_DIR="/home/user/public_html/project";
``` 
###Dumping from crontab
```sh
 * * * * * mysqldump -u root -p12345 tsusa_prod | gzip > `date +/home/user/Desktop/dump.sql.\%d_\%m_\%y_\%H_\%M_\%S.gz`
```
