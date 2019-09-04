# Written Questions:

Please answer the questions as thoroughly and completely as you can. The responses to the thought questions should be a paragraph in length. A paragraph should have a topic sentence, a conclusion, and be about five sentences in length. Organization goes a long way in producing quality work.

## Thought Questions: Part I
1. What does it mean to solve a problem?
Solving a problem means identifying something that needs to be fixed or made correct, and finding the appropriate route to make that happen. It can be in coding, in real life activities throughout the day, or in homework for other classes. Solving a problem takes a lot of tactical thinking, may not always be easy, and can take some time to figure out the task at hand. Problem solving is an important skill lesson to get used to doing.

2. Describe a process for solving a problem?
You should identify the problem, and know what you need fo fix. If you need to straighten out what's wrong with your code, you could look at the error that is produced and try to edit from there, or get a second pair of eyes to look over your work and try to identify the error in it. Once you know what's wrong, you can go ahead making changes; you might start by making a list of things you're going to do, or you could go ahead and start troubleshooting. If you're consistently working to no avail, you could ask the teacher for help.

3. When you become stuck in the problem solving process, what do you do?
When you get stuck, sometimes it's good to take some time away from your work to cool down, and come back later with a fresh mind. You should try not to get agitated, although it is fairly easy to become so. If you're stuck you shouldn't be afraid to ask the teacher for help if you're confused with what you're dealing with. The key in this is to keep going and to not give up, persistence is key. Once you get through a rough patch that you've been struggling with, you feels very good and accomplished, so just keep trying.

## Python & Syntax Exercises
1. If you put the following code in the Python interpreter, it will return an error:
```
    print('2)
```
Identify the error.
it is missing a parentheses after the 2


2. Explain the difference between
```Python
    print(5)
```
and
```Python
    print('5')
```
**Hint:** Saying that one contains single quotes and the other doesn't is not the response I'm looking for.
the first one is looking to evaluate what's inside the parentheses, but since there's only a five that's all it will print. the second is saying, to simply print whatever's inside the quotes, and that turns out to be only a 5.

3. Identify the *type* of the following:
    * ```x=2``` integer
    * ```y = 3.4``` floating point #
    * ```z = \pi``` <- The number pi floating point #
    * ```letter = 'z'``` variable
    * ```last = "Jackson"``` string
    * ```mol = [1, "xyz", 2]``` list

4. Consider the following code:
```Python
    string1 = "cat"
    string2 = "dog"

    print("Do you have a " + string1 + " or a " + string2 + "?")
```
Explain what is happening inside of the print statement.
Inside the parentheses there are 3 sets of quotes, so the computer is just printing what it sees inside those. But between the sets, it is seeing the variable 'string1' and 'string2' that were communicated earlier, so it copies in cat and dog in place of the variables, making the whole statement print out as 'Do you have a cat or a dog?'



## Thought Questions: Part II
1. What is a function? Why are they useful?
A function is a named sequence of code that are meant to carry out a certain task. They are useful for doing something that might be time consuming by hand, or for cutting down the amount of handwritten code for a particular assignment. Functions can be long or short, but they make life a lot easier I think when you're coding.


2. Where and how have you encountered functions before?
In class we went over chapter 3 about functions, so I learned a little about them there. We made a couple functions, one being to print lists of numbers and their square and cubed products. When you want to print that list, all you have to do is call the function, and it will print. In functions there is an input and an output, and the output is called the return value.

3. What kind of functions do you need to understand in order to make a robot travel from a corner to the middle of the room?
You might need to understand void functions, which perform an action but don't return a value? Because if you want the robot to move, you don't really need a number thrown back at you. The robot moving could be classified as a result, though. For the functions, you'd need to know what makes the robot move, which could be a function in of itself, then you'd need to know the route it would be taking to get to the middle of the room. You'd then call the function(s) for mobility in order of which they're needed, to take the robot to its destination. In the end, the whole route could be made into one big function.
(ask about this question)

## State Diagrams
(Please hand-in this portion in class, on the due date)

1. Consider the following code:
```Python
    x = 2
    y = 3

    y=y
```
Draw a state diagram for this code.

2. Consider the following code:
```Python
    x = 2
    y = 3
    y = x
```
Draw a state diagram for this code.

3. How do the two state diagrams differ? Why do they differ?
the state diagrams differ because in the second one, y's value changes. in the first one, y=y doesn't change the value so it stays 3, in the second y=x makes y not equal 2.
