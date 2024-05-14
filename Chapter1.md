# Chapter 1 - Introduction to Algorithm Design

## Finding Counterexamples
### Question 1-1:
*Show that a + b can be less than min(a,b).*

#### Reasoning
**Assume the opposite:**   There are no values for a,b where a+b < min(a,b).\
**Translation:**           a+b $\geq$ min(a,b); I am saying "a + b is always greater than or equal to min(a,b)."\
**Provide Counterexample:**
                        Let a = -1, b = -2;\
                        a + b = -1 + -2 = -3\
                        min(a,b) = min(-1,-2) = -2\
                        __________________________\
                        a + b $\geq$ min(a,b)\
                        -3 $\geq$ -2; NOT TRUE\
                        -3 $\lt$ -2
                        
**Conclusion:**         To prove that a + b can indeed be less than min(a,b), we disproved the opposite of that statement.\
                        By providing a counterexample, when a = -1 and b = -2, this showed that a + b is not always greater\
                        than or equal to min(a,b). And since it is not always greater than or equal to min(a,b), this meant\
                        that our original statement "a + b can be less than min(a,b)" is true.\
 ____________________________________________________________________________________________________________________________


### Question 1-2:
*Show that a x b can be less than min(a,b).*

#### Reasoning
To show that a * b can be less than min(a,b), I just need to find two numbers that, when multiplied, give me less.\
**Assume  the opposite:**   There are no values for a,b where a * b < min(a,b)\
**Translation:**            a * b $\geq$ min(a,b); \
**Provide Counterexample:**
                        Let a = -1, b = 10;\
                        a * b = -1 * 10 = -10\
                        min(a,b) = min(-1, 10) = -1\
                        ___________________________\
                        a * b $\geq$ min(a,b)\
                        -10 $\geq$ -1; NOT TRUE\
                        -10 $\lt$ -1

**Conclusion:**         To prove that a * b can be less than the min(a,b), we assumed the opposite was true.\
                        We assumed that a * b is always greater than or equal to min(a,b). By providing a\
                        counterexample to that statement, using a = -1 and b = 10, we proved that our original\
                        statement is true: a * b can be less than min(a,b) when a = -1 and be = 10.\
____________________________________________________________________________________________________________________________


### Question 1-4:
*Design/draw a road network with two points a and b such that the shortest route\
between a and b is not the route with the fewest turns.*

#### Thought-Process
1) Simplify the goal: Shortest route from a -> b does not have the fewest turns.
2) Counterexample: A longer route a -> c -> b has fewer turns.
3) Counterargument: Just because a route has fewer turns does not mean it is the shortest route.
4) Conclusion: To design a route from point a to point b so that the shortest route between them was not the\
one with the fewest turns, I started by creating another problem. Instead of designing a short route that\
did not have the fewest turns (a to b), I created a longer route (a to c to b) that had fewer turns. Then,\
I created the shortest route (a to b) that had more turns than the longer route (a to c to b).

____________________________________________________________________________________________________________________________