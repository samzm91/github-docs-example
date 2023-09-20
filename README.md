# Github Docs Example

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy/past/share code**.

A good  __Cloud Eng__  uses codeblocks whenever possible.

```
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number:"
number = gets.chomp.to_i

if number < 0
  puts "Factorial is not defined for negative numbers."
elsif number == 0
  puts "The factorial of 0 is 1."
else
  result = factorial(number)
  puts "The factorial of #{number} is #{result}."
end
```

- when you can you should attempt  tp apply syntax highlighting to you codeblocks

``` ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number:"
number = gets.chomp.to_i

if number < 0
  puts "Factorial is not defined for negative numbers."
elsif number == 0
  puts "The factorial of 0 is 1."
else
  result = factorial(number)
  puts "The factorial of #{number} is #{result}."
end
```
![licensed-image](https://github.com/samzm91/github-docs-example/assets/30095438/4200db86-9bb6-4bfa-9705-47b34561f2d7)

Sun image imported and  resize it
<img width="200px" src="https://github.com/samzm91/github-docs-example/assets/30095438/4200db86-9bb6-4bfa-9705-47b34561f2d7" />

```bash
Traceback (most recent call last):
  example.rb:2:in 'print_variable'
  example.rb:6:in '<main>'
NameError: undefined local variable or method `undefined_variable' for main:Object
```
> here's an example of error code in ruby
