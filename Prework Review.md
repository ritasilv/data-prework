# Rita Silva

Hello Rita! You have submitted the Prework, what is the first step in Ironhack, congrats! Many of your questions are followed by a great logical thought behind them! Keep working and fighting with the code! 

Let's go with the corrections!

## 1. Snail and the well

In this exercise you had to understand how to deal with `while` loops and it seems that you did, great!

Inside the loop, be careful with the identation levels, if you want to learn more about it, check this link or ask me! 

https://kkiesling.github.io/python-novice-gapminder-custom/06-for-loops/

The main question is almost perfect, but the correct answer is adding an if condition for the distance lost during the night. It will be something like this:
```python
while snail_position <= well_height:
    days += 1
    snail_position += daily_distance
    if snail_position <= well_height:
        snail_position += nightly_distance
```

In the bonus, the logical thought behind the task was similar to the one above, where you showed that you are able to solve the exercise, if you have enough time, give it a try, certainly you can solve it!

## 2. Duel of sorcerers

Great! Here you used the `zip` function, which will be very useful in the future! 

You have the main question almost perfect, you just have to switch the positions of the variables inside the `zip` function, good work!

In the bonus you had to do a similar exercise but, in this case, you had to deal with dictionaries.

Here I attach you how to iterate through dictionaries: 
https://realpython.com/iterate-through-dictionary-python/

If you have any question about it, don't hesitate to ask me!

Good job working with the `while` loop, that was the main task in this exercise!

## 3. Bus

Here you had to work with a list of `tuples` and iterate through it. It seems that you were so close to solve it once again, that's cool, you just have to keep fighting with the code a bit more! 

Your solution should be something like this: 
```python 
passengers_at_stop = []
total = 0
for on, off in stops:
    total += on - off
    passengers_at_stop.append(total)
```

## 4. Robin Hood

Don't worry if you couldn't try this exercise, it was such a difficult one. 
Basically, in this assignment you had to work with point of coordinates, `for` loops and `if` conditions. 

I encourage you to try this exercise in a couple of weeks, you will be able to solve it and you will change frustration into satisfaction! 

If you have any question, tell me!

## 5. Temperature

Good work here! You understood how to work with operators, so that's perfect!

In the estimator question you had two options:
1. Replace the value with the mean that you calculated before.
2. Sum the values in indexes 2 and 4 and divide it by two. 

Moreover, you used `numpy` library, that's cool! You solved in a really good way question #7 using operators inside an `if` condition, good job!


## 6. Robin Hood

Great Rita! You gave a try to this exercise, congrats! That's the kind of effort that you have to do, great!

Well done using the `input` function and making the code more robust.

Again, be careful with identations, they are so important. Your logical thought here is really good, so I'm gonna attach you a link explaining how to define a function. They are really useful to save time and lines of code. 

https://www.w3schools.com/python/python_functions.asp

Good work, Rita, I'm very happy that you have tried it, as I said to you, that's the main goal here!!

