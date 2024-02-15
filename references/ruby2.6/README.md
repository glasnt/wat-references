# Ruby

[ruby-lang.org](https://www.ruby-lang.org/en/)

## Run these examples yourself

### docker

```
# Run the launch helper for the current directory
. ../launch ${PWD##*/}
```

### macOS

```
brew install ruby
irb
```

# Order of operands


[Precedence, ruby-doc.org](https://ruby-doc.org/3.3.0/syntax/precedence_rdoc.html)

[More information, tumblr](https://whatthefuckruby.tumblr.com/post/70164947137/irb-not-true-false-true-irb-not-true)


# Implicit return

```ruby
def mymethod
    a = "apple" 
    b = "banana" # last value touched is returned. 
end

b = mymethod
puts b
```
https://franzejr.github.io/best-ruby/idiomatic_ruby/implicit_return.html

# flip floperator

https://www.youtube.com/watch?v=BmWLhVMWC9I&t=783s

https://perldoc.perl.org/perlop#Range-Operators

https://chrisseaton.com/truffleruby/flip-flops/

https://blog.saeloun.com/2020/01/06/ruby-2-7-revert-flip-flop-operator-deprecation/