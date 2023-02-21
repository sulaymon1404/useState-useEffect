# useState-useEffect

# useState


#### Import useState
# To use the useState Hook, we first need to import it into our component.
![](/images/1.PNG)
# Notice that we are destructuring useState from react as it is a named export.

## We initialize our state by calling useState in our function component. useState accepts an initial state and returns two values:.

- The current state
- A function that updates the state.

![](/images/2.PNG)

# Notice that again, we are destructuring the returned values from useState.

# The first value, color, is our current state.

# The second value, setColor, is the function that is used to update our state.
# These names are variables that can be named anything you would like.
# Read State
#### We can now include our state anywhere in our component.

![](/images/3.PNG)

# Update State
## To update our state, we use our state updater function.

# We should never directly update state. Ex: color = "red" is not allowed.
![](/images/4.PNG)
# What Can State Hold
## The useState Hook can be used to keep track of strings, numbers, booleans, arrays, objects, and any combination of these!
#We could create multiple state Hooks to track individual values.

![](/images/5.PNG)

# React useEffect Hooks
# The useEffect Hook allows you to perform side effects in your components.
# Some examples of side effects are: fetching data, directly updating the DOM, and timers.
# useEffect accepts two arguments. The second argument is optional.
# useEffect(<function>, <dependency>)

# Let's use a timer as an example.

![](/images/6.PNG)
