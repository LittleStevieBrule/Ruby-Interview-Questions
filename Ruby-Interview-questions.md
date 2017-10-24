# Ruby Interview Questions
#### What is a class?
>
>
> 
>
>
>
>


#### What is an Object?
>
>
>
>
>


#### What is a module? Can you tell me the difference between classes and modules?
>
>
>
>
>



#### Explain the following code:
```ruby
a ||= 'a'   
```
>
>
>
>
>
>

##### What does the following code evaluate to?
```ruby
["one", "two", "three"].map {|n| puts n.upcase }
```
>
>
>
>
>
>
>
>
>
>
>

#### Define a function that that sorts the keys of a hash by length
For example:
```ruby
hash = { 'abc' => 'hello', 'another_key' => '123', '8080' => 'third' }
your_function(hash) #Result: ['abc'. '8080', 'another_key']
```
>
>
>
>
>
>
>
>
>
>
>
>
>
>
>



#### Which of the following will throw a NoMethodError Given the below code?
a) ` A.new.test`

b) ` A.test`

c) ` B.test`

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
>
>
>
>
>
>

#### What is the result of the following code?
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

A.new.meth_1
A.new.meth_2
```
>
>
>
>
>
>
