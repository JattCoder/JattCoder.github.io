---
layout: post
title:      "Ruby Self Object"
date:       2020-04-16 19:09:28 +0000
permalink:  ruby_self_object
---


Anything we write in Ruby is an object and every piece of code, belongs to some object. Variable self in Ruby is very special variable, it owns the excuted code. Whenever you read or write a program self is there in the back of the mind. It can be used anywhere,  inside the method or to the method in an class.


```
class Student
  def initialize(stu)
    @stu_name = stu
    p self
  end
end

student = Student.new("John")
p student
```

The Output will be something like this.

```
#<Student:0x882p7727439248 @name="John">
#<Student:0x882p7727439248 @name="John">
```

As you can see we output the same object twice. Once in the initialize method using p self, and once in the outer scope using p person. You can also see that the cryptic looking object id is the same for both instances. So we can know it’s indeed the very same object.
