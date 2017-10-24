# Ruby Interview Questions

##### What does the following code evaluate to?
```ruby
[1, 2, 3].map {|n| puts n + 1 }
[1, 2, 3].each {|n| puts n + 1}
```
Answer:

```ruby
[nil, nil, nil]
[1, 2, 3]
```




#### Which of the following will throw a NoMethodError Given the below code?
a) `A.new.test`

b) `A.test`

c) `B.test`

```ruby
module Mod

  def test
    'test'
  end

end

class A
  include Mod
end

class B
  extend Mod
end

```
Answer: b

#### What is the result of the following code?
```ruby
class A
  def meth_1
    1
  end

  def meth_2
    2
  end

end

class A
  def meth_1
    'one'
  end

  def meth_3
    'three'
  end
end

A.new.meth_1
A.new.meth_2
A.new.meth_3
```
Answer:
```ruby
A.new.meth_1 #=> 'one'
A.new.meth_2 #=> 2
A.new.meth_3 #=> 'three'

```
