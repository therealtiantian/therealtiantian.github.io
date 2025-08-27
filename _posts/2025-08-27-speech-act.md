---
layout: post
title: The Consequence of Speech Act
subtitle: J. L. Austin, John Searle, and creatio ex nihilo
tags: [linguistics, CS]
---
The speech act theory proposed by J. L. Austin and developed by John Searle has a profound correlation with computer science language. According to Searle, a lot of things are done through words and words only, which originates from the Christian idea of “the Word is God” (*καὶ θεὸς ἦν ὁ λόγος*). God creates with words, (simultaneously *being* the words Himself,) but human beings do not have the ability to create *ex nihilo*, so they have to be content with *altering* the world with words. Actions like marriage, war-declaration, promise-making are all completed with words. 

The virtual world is different from the concrete one in that we can create something out of nothing in the former, and this action is done by speech acts exactly. Consider the action of defining a class, the class is created by declaring its definition, and then capitalizing the class’ first letter:
```python

class Person:
    def __init__(self, firstname, lastname):
        self.fn = firstname
        self.ln = lastname      
```

And when the class is defined, instances are created by purely announcing them with the class to which they belong:
```python

tian = Person("Tian", “Tian")

```
Compare that with another method:
```python

num = '1001'
a = int(num)

```
The above method casts the string to another type, namely integer. the function `int( )` does not capitalize the first letter, and this is a function that *alters*, instead of *creates*. This is analogous to human being’s behavior in the real world, changing matters so that they appear as a different texture (imagine a chemist putting matters together for another matter out of reaction). But the capitalized instantiation function is analogous to God’s creation *ex nihilo*. 