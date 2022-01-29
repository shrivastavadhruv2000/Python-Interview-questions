# Python-Interview-questions
Q.1 What is Range() Function?<br/>
Ans: The range() function can produce an integer sequence at runtime. For example, a statement like range(0, 10) will generate a series of ten integers starting from 0 to 9.


Q.2 What is the difference between Python Arrays and lists?<br/>
Ans: Arrays and lists, in Python, have the same way of storing data. But, arrays can hold only a single data type elements whereas lists can hold any data type elements.

Example:<br/>


import array as arr<br/>
My_Array=arr.array('i',[1,2,3,4])<br/>
My_list=[1,'abc',1.20]<br/>
print(My_Array)<br/>
print(My_list)<br/>

Output:<br/>

array(‘i’, [1, 2, 3, 4]) [1, ‘abc’, 1.2]<br/>


Q3. What are functions in Python?<br/>
Ans: A function is a block of code which is executed only when it is called. To define a Python function, the def keyword is used.<br/>


Q4.What is a lambda function?<br/>
Ans: An anonymous function is known as a lambda function. This function can have any number of parameters but, can have just one statement.<br/>

Example:<br/>

a = lambda x,y : x+y<br/>
print(a(5, 6))<br/>
Output: 11<br/>


Q5. What is the usage of help() and dir() function in Python?<br/>
Ans: Help() and dir() both functions are accessible from the Python interpreter and used for viewing a consolidated dump of built-in functions. <br/>

Help() function: The help() function is used to display the documentation string and also facilitates you to see the help related to modules, keywords, attributes, etc.<br/>
Dir() function: The dir() function is used to display the defined symbols.<br/>


Q6. What is a dictionary in Python?<br/>
Ans: The built-in datatypes in Python is called dictionary. It defines one-to-one relationship between keys and values. Dictionaries contain pair of keys and their corresponding values. Dictionaries are indexed by keys.

Let’s take an example:<br/>

The following example contains some keys. Country, Capital & PM. Their corresponding values are India, Delhi and Modi respectively.<br/>


dict={'Country':'India','Capital':'Delhi','PM':'Modi'}<br/>

print dict[Country]<br/>
Output:India<br/>


Q7. How can the ternary operators be used in python?<br/>
Ans: The Ternary operator is the operator that is used to show the conditional statements. This consists of the true or false values with a statement that has to be evaluated for it.<br/>

Syntax:<br/>

The Ternary operator will be given as:<br/>
[on_true] if [expression] else [on_false]x, y = 25, 50big = x if x < y else y<br/>

Example:<br/>

The expression gets evaluated like if x<y else y, in this case if x<y is true then the value is returned as big=x and if it is incorrect then big=y will be sent as a result.<br/>

                                                                      
Q8. What are the three main conditional statements in Python?<br/>
Answer:
if, elif, and else<br/>

Q9. Illustrate a basic if, elif, else structure.<br/>
Answer:
if <condition>:<br/>
. . .<br/>
elif<another condition>:<br/>
. . .<br/>
else:<br/>
. . .<br/>

  
Q10. What are the comparison operators in Python?<br/>
Answer:< Less than, > Greater than, <= Less than or equal to, >= Greater than or equal to, = Equal to, != not equal, o alternative not equal. Note a single = is NOT a Python comparison operator, it is an assignment operator only.<br/>
  
  
Q11. How is the Python switch statement used?<br/>
Answer:This is a trick question, there is no built-in switch statement in Python, which is unusual. A switch statement can be easily created using if-elif using lambda or with Python dictionaries.<br/>
