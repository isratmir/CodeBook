```
\s - whitespace
\n - newline
\} - } symbol
\b\w+\b  - select all words
<(.*?)>  - everything like <div class="col-xs-12">
[a-z0-9_.]+(jpeg|jpg|png|gif)  - "http://localhost/./files/pictures/picture_532.png"
\d{2,3} - Number of digits
[<a-z"-=;&/\d>]* - HTML tags on page
(?!})., - Select all commas except one after closing curly brace.
```
