# Ruby Interview Questions
#### What is a class?
```
Your Answer:








```
    
#### What is an Object?
```
Your Answer:








```

#### What is a module? Can you tell me the difference between classes and modules?
```
Your Answer:








```

#### Explain the ruby idiom: `a ||= b`

```
Your Answer:








```

##### What does `upcased` equal in the below code?
```ruby
upcased = ["one", "two", "three"].map {|n| puts n.upcase }
```
```
Your Answer:








```
#### Define a function that that sorts the keys of a hash by length
For example:
```ruby
hash = { 'abc' => 'hello', 'another_key' => '123', '8080' => 'third' }
your_function(hash) #Result: ['abc'. '8080', 'another_key']
```
```
Your Answer:















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
```
Your Answer:


```
#### Given the following code what is the result of `A.new.meth_1`? `A.new.meth_2`?
```ruby
class A
  def meth_1
    1
  end
end

class A 
  def meth_2
    2
  end
end
```
```
Your Answer:






```