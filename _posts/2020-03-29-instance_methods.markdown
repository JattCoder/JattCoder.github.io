---
layout: post
title:      "Instance Methods"
date:       2020-03-30 02:27:30 +0000
permalink:  instance_methods
---


The Most Importnt thing to understand about instance methods is Instance Methods can only be called on a particular instance of the class.

```
student = Student.new  
=> #<Student:0x007fd2e446c7b0>

student.all  
=> [] 
```

If we try to call an instance method directly on the class, it will give us an error

```
Student.all  
NoMethodError: undefined method ‘all’ for Student:Class 
```
