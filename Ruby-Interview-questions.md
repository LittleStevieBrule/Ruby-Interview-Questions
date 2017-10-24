# Ruby Interview Questions
#### What is a class?
<pre>
Your Answer:










</pre>


#### What is an Object?
<pre>
Your Answer:










</pre>


#### What is a module? Can you tell me the difference between classes and modules?
<pre>
Your Answer:










</pre>



#### Explain the following code:
```ruby
a ||= 'a'   
```
<pre>
Your Answer:









</pre>


##### What does the following code evaluate to?
```ruby
["one", "two", "three"].map {|n| puts n.upcase }
```
<pre>
Your Answer:









</pre>


#### Define a function that that sorts the keys of a hash by length
For example:
```ruby
hash = { 'abc' => 'hello', 'another_key' => '123', '8080' => 'third' }
your_function(hash) #Result: ['abc'. '8080', 'another_key']
```
<pre>
Your Answer:













</pre>



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
<pre>
Your Answer:









</pre>



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
<pre>
Your Answer:









</pre>
