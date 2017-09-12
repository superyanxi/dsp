# Learn Python

Read Allen Downey's [Think Python](http://www.greenteapress.com/thinkpython/) for getting up to speed with Python 2.7 and computer science topics. It's completely available online, or you can buy a physical copy if you would like.

<a href="http://www.greenteapress.com/thinkpython/"><img src="img/think_python.png" style="width: 100px;" target="_blank"></a>

For quick and easy interactive practice with Python, many people enjoy [Codecademy's Python track](http://www.codecademy.com/en/tracks/python). There's also [Learn Python The Hard Way](http://learnpythonthehardway.org/book/) and [The Python Tutorial](https://docs.python.org/2/tutorial/).

---

### Q1. Lists &amp; Tuples

How are Python lists and tuples similar and different? Which will work as keys in dictionaries? Why?

>> REPLACE THIS TEXT WITH YOUR RESPONSE

---**Both python and tuples are sequence structure and they can contain any type of objects. Tuples are immutable which can't be inserted and deleted. Lists are mutable which can be changed. Tuples can be used  as keys in dictionaries due to their immutability.**

### Q2. Lists &amp; Sets

How are Python lists and sets similar and different? Give examples of using both. How does performance compare between lists and sets for finding an element. Why?


>> REPLACE THIS TEXT WITH YOUR RESPONSE

---**Sets are mutable unordered sequence of unique elements. Sets can contain repeated elements.
i.e a = set([1,2,3])
a = {1,2,3}
set should faster for finding an elements.Since sets only contain unique elements so it would have to search whole set to find the elements in general.**

### Q3. Lambda Function

Describe Python's `lambda`. What is it, and what is it used for? Give at least one example, including an example of using a `lambda` in the `key` argument to `sorted`.

>> REPLACE THIS TEXT WITH YOUR RESPONSE

---**lambda is anonymous function. It is often used in conjunction with typical functional concepts like filter(),map() and reduce().
i.e sorted(["apple","banana","Cherry","pear"],key = lambda word: word[1])
['banana', 'pear', 'Cherry', 'apple']**


### Q4. List Comprehension, Map &amp; Filter

Explain list comprehensions. Give examples and show equivalents with `map` and `filter`. How do their capabilities compare? Also demonstrate set comprehensions and dictionary comprehensions.

>> REPLACE THIS TEXT WITH YOUR RESPONSE

---List comprehensions provide a concise way to create lists. It consists of brackets containing an expression followed by a for clause then zero or more for or if clauses.
i.e:
items = [1,2,3,4,5,6]
square1 = [x**2 for x in items]
square1 = list(map(lambda x: x**2, items))

i.e
items = [1,2,3,4,5]
evennumber = [x for x in items if x%2 == 0]
evennumber = list(filter(lambda x: x%2 == 0, items))

### Complete the following problems by editing the files below:

### Q5. Datetime
Use Python to compute days between start and stop date.   
a.  

```
date_start = '01-02-2013'    
date_stop = '07-28-2015'
```

>> REPLACE THIS TEXT WITH YOUR RESPONSE (answer will be in number of days)

b.  
```
date_start = '12312013'  
date_stop = '05282015'  
```

>> REPLACE THIS TEXT WITH YOUR RESPONSE (answer will be in number of days)

c.  
```
date_start = '15-Jan-1994'      
date_stop = '14-Jul-2015'  
```

>> REPLACE THIS TEXT WITH YOUR RESPONSE  (answer will be in number of days)

Place code in this file: [q5_datetime.py](python/q5_datetime.py)

---

### Q6. Strings
Edit the 7 functions in [q6_strings.py](python/q6_strings.py)

---

### Q7. Lists
Edit the 5 functions in [q7_lists.py](python/q7_lists.py)

---

### Q8. Parsing
Write a script as indicated (using the football data) in [q8_parsing.py](python/q8_parsing.py)
