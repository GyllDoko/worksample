
`What is self ?`

> It’s a Ruby keyword that gives you access to the current object.
> This “current object” depends on the context.
> the context is where your code is at any given moment.
> If your code is inside an instance method, self is an instance of that class. In other words, self is an object

`How to use self ?`

> We can use self for disanbiguation

```
class Example
  def do_something
    banana = "variable"

    puts banana
    puts self.banana
  end

  def banana
    "method"
  end
end

Example.new.do_something

# "variable"  => puts banana
# "method"    => puts self.banana
```
in this example ☝️ self is using to tell the difference between a method and a local variable.

> We can use self to define a class-level methods

```
class Salad
  def self.buy_olive_oil
    # ...
  end
end

Salad.buy_olive_oil
```

in this example ☝️ we can call an instance method of the class out of it. It make the code better to read and eaisier to change if we change the class.


