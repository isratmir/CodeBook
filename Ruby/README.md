####Arrays
```ruby

[1, 2, 3, 4, 5].map { |i| i + 1 }

names = ['rock', 'paper', 'scissors', 'lizard', 'spock']
names.select {|word| word.length > 5 }

[1,3,5,4,6,7].delete 5

[1,2,3,4,5,6,7,8,9].delete_if {|i| i%2==0}

[1, 2, 3, 4, 5]<<"woot"

[1, 2, 3, 4, 5].push "woot"
```

####String
```ruby
'Fear is the path to the dark side'.split(' ')

'Ruby' + 'Monk'
"Ruby".concat("Monk")
```
####Replacing a substring
```ruby
"I should look into your problem when I get time".sub('I','We')
"I should look into your problem when I get time".gsub('I','We')
'RubyMonk Is Pretty Brilliant'.gsub(/[A-Z]/, '0')
'RubyMonk Is Pretty Brilliant'.match(/ ./, 9)

####Boolean
!(name=='Bob')
```
###Examples

```ruby
def sort_string(string)
  string.split(' ').sort{|x, y| x.length <=> y.length}.join(' ')
end

def random_select(array, n)
  result = []
  n.times do 
    result << array[rand(array.length)]
  end
  result
end

is_an_experienced_ruby_programmer =
  (candidate.languages_worked_with.include? 'Ruby') &&
  (candidate.years_of_experience >= 2 || candidate.github_points >= 500) &&
  ! (candidate.age < 15 || candidate.applied_recently?)

def palindrome?(sentence)
  s = sentence.downcase.gsub(" ","")
  s == s.reverse
end

def sum_of_cubes(a, b)
  (a..b).inject(0) { |sum, x| sum += (x*x*x) }
end

def non_duplicated_values(values)
  unique = []
  values.map do |i|
    if values.count(i) < 2
      unique << i
    end
  end
  unique
endef sort_string(string)
  string.split(' ').sort{|x, y| x.length <=> y.length}.join(' ')
end
```
