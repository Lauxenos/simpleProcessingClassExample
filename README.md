# simpleProcessingClassExample



Suppose you wanted a circle (or a ball) bouncing around in a box. You
might do something like
this:

[Step 1](src/step1/step1.pde)



Copy this code into a new Processing sketch and run it. Read the code and
understand what it’s doing.

Now suppose you wanted two balls, or 10, or 100. You’d have to copy all of
that again and again. After copying it 5 or 6 times you might ask yourself
if there isn’t a better way.

You might notice, for instance, that most of the code is exactly the same, 
it’s just dealing with a
different ball. Wouldn’t it be nice to
describe the ball behaviour once, and then have it automatically know how to
do that to all the balls?

There is a way, using classes and objects. Here is the same program using
objects:

[Step 2](src/step2/step2.pde)

If you want two balls, you don’t need to redefine the class, just create
more objects:

[Step 3](src/step3/step3.pde)

But that seems like the class didn’t really save us that much work. Why use
classes? Answer: it really
helps when you want to make lots of objects, and you use arrays instead of
individual names for each
object:

[Step 4](src/step4/step4.pde)
