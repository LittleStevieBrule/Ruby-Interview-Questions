Interview questions 10/24/17
## General
Have you worked in/with QA before? What was your experience like?

Describe the project you've worked on that you're most proud of. What did you do that worked out particularly well?

Describe the project you've worked on that you're least proud of. What would you do differently?

What are your experiences using linux?


<pre>









































































</pre>

## Ruby

What is a Module in Ruby?

What is a block in Ruby?

What are differences between `extend` and `include` in Ruby?

What do both of these lines of Ruby code evaluate to?
```ruby
['1', '2', '3'].map { |n| puts(n.to_i + 1) }
[1, 2, 3].each { |n| puts n + 1 }
```
<pre>






































</pre>
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

<pre>


























</pre>
