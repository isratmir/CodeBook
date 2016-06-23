```ruby

[1, 2, 3, 4, 5].map { |i| i + 1 }

names = ['rock', 'paper', 'scissors', 'lizard', 'spock']
names.select {|word| word.length > 5 }

[1,3,5,4,6,7].delete 5

[1,2,3,4,5,6,7,8,9].delete_if {|i| i%2==0}

[1, 2, 3, 4, 5]<<"woot"

[1, 2, 3, 4, 5].push "woot"

'Fear is the path to the dark side'.split(' ')

'Ruby' + 'Monk'
"Ruby".concat("Monk")
```
###Replacing a substring
```ruby
"I should look into your problem when I get time".sub('I','We')
"I should look into your problem when I get time".gsub('I','We')
'RubyMonk Is Pretty Brilliant'.gsub(/[A-Z]/, '0')
'RubyMonk Is Pretty Brilliant'.match(/ ./, 9)

Boolean
!(name=='Bob')

def sort_string(string)
  string.split(' ').sort{|x, y| x.length <=> y.length}.join(' ')
end

```
