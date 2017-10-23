# Ruby Interview Questions
#### What is a class?
A text-book answer: classes are a blue-print for constructing computer models
for real or virtual objects
In reality: classes hold data, have methods that interact with that data,
   and are used to instantiate objects.
   
#### What is an Object?
Answer:
  An instance of a class.
  To some, it's also the root class in ruby (Object).
  
#### What is a module? Can you tell me the difference between classes and modules?
Answer: 
  Modules serve as a mechanism for namespaces.
  Also, modules provide as a mechanism for multiple inheritance via mix-ins and 
  cannot be instantiated like classes can.

#### Explain the ruby idiom: `a ||= b`

Answer:
if `a` then `a` else `a` equals `b`

`a || a = b `

##### What does `upcased` equal in the below code?
```ruby
upcased = ["one", "two", "three"].map {|n| puts n.upcase }
```
Answer: `[nil,nil,nil]`

#### Define a function that that sorts the keys of a hash by length
For example:
```ruby
hash = { 'abc' => 'hello', 'another_key' => '123', '8080' => 'third' }
your_function(hash) #Result: ['abc'. '8080', 'another_key']
```
Answer:
```ruby
def meth(hash) 
  hash.keys.map{|key| key.to_s}.sort_by { |key| key.length }
end
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
Answer: 
```ruby
A.new.meth_1 #=> 1
A.new.meth_2 #=> 2
  
```
