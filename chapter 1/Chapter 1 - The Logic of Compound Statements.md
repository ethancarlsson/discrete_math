# 1.1 Logical Forma and Logical Equivalence
- Central concept of deductive logic is the argument form. 
	- an argument is a series of statements that together assert the truth of a statement
	- the assertion at the end of a sequence is a *conclusion*
	- the statements coming before the conclusion are *premises*
- Logical analysis will help you determine whether or not  conclusion follows *necessarily* from its premises

## Statements
- A statement is a sentence that is true or false but not both
- "two plus one equals three" is a statement because it is true
- "two plus two equals three" is a statement because it is false
- "He is a college student" is not a statement because it relies on the value "he" to determine truth or falsity. We don't know who he is so we can't make any more complex statemens about him. For some values "he" it will be true and for some values "he" it will be false.
- "x+y > 0" is not a statement because for some values y and x it is true and for some it is false. If we say x=1 and y=2 beforehand then we can say that it is true and we can say that it is a statement

## Compound Statements
### Symbols
- ~ denotes "not"
- ^ denotes "and"
- v denotes "or"

#### Example 1.1.2: Translating from English to Symbols
- It is not hot but it is sunny
	- it is ~hot ^ is sunny
		- ~h ^ s
- It is neither hot nor sunny
	- it is ~hot ^ ~sunny
		- ~h ^ ~s

#### Example 1.1.4
- suppose x is a particular real number. 
	- p = "0 < x"
	- q = "x < 3"
	- r = "x == 3"
a. x <= 3: q V r
b. 0 < x < 3: p ^ q
c. 0 < x <= 3: p ^ (q ^ r)

## Truth values
- if *p* is a statement variable, the negation of *p* is "not *p*" and is denoted ~p; It has the opposite truth value to *p*.
	- if *p *== True; not *p* == False