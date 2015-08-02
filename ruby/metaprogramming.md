# Ruby - Metaprogramming

## Define a singleton method
_A singleton method is a method that belongs only to a particular object. Class methods are singleton methods that belong to a class object._
```rb
foo = "123"
def foo.bar
  "#{self}!"
end
foo.bar # => 123!
```

