Given this code:
```ruby
class A
  def one
    1
  end

  def two
    2
  end
end

class A
  def one
    'one'
  end

  def three
    'three'
  end
end

```

What is the result of the following lines of code?
```ruby
A.new.one
A.new.two
A.new.three
```
