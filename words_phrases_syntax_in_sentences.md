## Words, phrases, and syntax with contexts
### - which I didn't know, had forgotten, or had known but don't have a good command of.
- str.join() **takes us in the other direction**, **sewing** a list of strings **up into** one long string, using the string it was called on as a separator.  
 - If we want to **throw in** any non-string objects, we have to be careful to call str() on them first.
 - We call .format() on a "format string", **where** the Python values we want to insert are represented with {} placeholders.
 - Notice how we didn't **even** have to call str() to convert position from an int. 
 - format() **takes care of that for** us.
 - **If that was all that** format() **did**, it **would still be** incredibly useful.
 - But **as it turns out**, it can do a lot more. **Here's just a taste**:
 - Anything that is not contained in braces is considered literal text, which **is copied unchanged to the output**. 
 - You could probably write a short book just on str.format, so I'll stop here, and **point you to** pyformat.info and the official docs for further reading.
 - Dictionarie**s** are **a** built-in Python data **structure** for **mapping keys to values**.
 - In this case 'one', 'two', and 'three' are the keys, and 1, 2 and 3 are **their corresponding** values.
 - Values **are accessed via** square bracket syntax similar to **indexing into lists and strings**.
 - Return a **right-justified** string of length width.
 - You are almost **done with** the course. Nice job!
 - Let's start with a string **lightning round** to warm up. 
 - **What are the lengths of** the strings below?
 - For each of the five strings below, predict what len() would return **when passed** that string. 
 - Note that the empty string is also the only string that Python **considers as** False **when converting** to boolean.
 - Make a transformed list where we 'normalize' each word to **facilitate** matching.
 - Periods and commas are removed from the end of each word, and it's **set to** all lowercase.
 - **Is there a match?** **If so,** update the list of matching indices.
 - Now the researcher wants to supply multiple **keywords to search for**. 
 - Reusing code **in this way** makes your programs more robust and readable - and it saves typing!
 - Returns a dictionary **where** each key is a keyword, and the value is a list of indices (from doc_list) of the documents containing that keyword
 - **Based only on this information**, if you receive a random letter, **the best guess is a 40% chance of it being** spam.
 - Based on this sample, if you know that a mail contains the word "offer", **there is a 75% chance of being** spam.
 - **Knowing this can help you make** a better decision **when filtering out** unwanted spam mail.
 - But **even the best programmers rely heavily on** "libraries" of **code** from other programmers.
 - In this tutorial, you will learn about imports in Python, **get some tips for working with** unfamiliar libraries (and the objects they return), and **dig into** operator overloading.
 - So far we've talked about types and functions which **are built-in to** the language.
 - But one of the best things about Python (especially if you're a data scientist) is **the vast number of** high-quality custom libraries that have **been written for it**.
 - Some of these libraries are in the "standard library"**, meaning** you can find them **anywhere you run** Python. 
 - Other libraries can be easily added, **even if** they **aren't always shipped with** Python.
 - **Either way,** we'll **access** this code **with** imports.
 - We can access these variables **using** dot syntax. 
 - Some of them **refer to** simple values, like math.pi
 - Of course, if we don't know **what** math.log **does**, we can **call** help() **on** it
 - If we know **we'll be using** functions in math frequently we can **import it under a shorter alias** to save some typing (though in this case "math" is already pretty short).
 - This tutorial will **guide you through some of the common uses** of formatters in Python, which **can help make** your code and program more readable and user friendly.
 - You should **have Python 3 installed and a programming environment set up** on your computer or server.
 - Formatters work by **putting in** one or more replacement fields or placeholders — defined by a pair of curly braces {} — **into** a string and calling the str.format() method. 
 - You’ll **pass into** the method the value you want to concatenate with the string. 
 - This value will be **passed through in** the same place that your placeholder is positioned when you run the program.
 - This **places** the value of 5 **into** the string where the curly braces were:
 - We can also **assign a variable to be** equal to the value of a string that has formatter placeholders:
 - My boss **assigned me to give** a presentation seminar in New York. 
 - Formatters in Python **allow you to use** curly braces as placeholders for values that you’ll **pass through with** the str.format() method.
 - You can use multiple pairs of curly braces **when using** formatters.
 - Then, we **passed** two strings **into** the str.format() method, **separating them by a comma**.
 - When we **leave** curly braces **empty** without any parameters, Python will **replace** the values passed through the str.format() method in order. 
 - Imports, operator overloading, and survival tips for **venturing into** the world of external libraries
 - But one of the best things about Python (especially if you're a data scientist) is **the vast number of** high-quality custom libraries **that have been written for** it.
 - Some of these libraries **are in** the "standard library", **meaning you can** find them **anywhere you run** Python. 
 - Other libraries can be easily added, **even if they aren't always shipped with** Python.
 - **Either way,** we'll access this code with imports.
 - But **most of what we'll find** in the module are functions, like math.log:
 - Of course, if we don't **know what math.log does**, we can call help() on it:
 - This **will give us the combined documentation** for all the functions and values in the module (**as well as** a high-level description of the module). 
 - If we know **we'll be using** functions in math **frequently** we can import it under a shorter alias to **save some typing** (though in this case "math" is already pretty short).
 - You **may have seen** code that does this with certain popular libraries like Pandas, Numpy, Tensorflow, or Matplotlib. 
 - For example, **it's a common convention to import** numpy as np and import pandas as pd.
 - **Wouldn't it be** great if we could refer to all the variables in the math module by themselves?
 - Bad news: some purists **might grumble at you for doing this**.
 - Worse: they **kind of have a point**.
 - **What has happened? It worked before**!
 - **These kinds of "star imports"** **can occasionally lead to** weird, difficult-to-debug situations.
 - **Something to be aware of is that** they can also have variables referring to other modules.
 - So if we import numpy **as above**, then **calling** a function in the random "submodule" **will require** two dots.
 - For example, if you work with the graphing library matplotlib, you'll **be coming into contact with** objects it defines which represent Subplots, Figures, TickMarks, and Annotations. 
 - **In the cell above,** we saw that calling a numpy function gave us an "array". 
 - Or maybe I just want to turn the array into a list, **in which case** I can use "tolist"
 - Return a **contiguous** flattened array.
 - What's the value of **the below expression**?
 - Technically, **there’s nothing that stops you from using** getter and setter methods in Python. 
 - However, **it’s bad practice to** violate this convention.
 - **From this code, you can confirm that** Python doesn’t restrict access to non-public attributes.
 - **Whether or not you do so is up to you.**
 - This code **uncovers a fundamental principle**. 
 - However, how can you handle requirement changes that **would seem to involve** API changes?
 - Once you **have** these three methods **in place**, you **create** a class attribute called .radius to store the property object. 
 - **That way,** you know exactly which method **goes into** each argument.
 - **To give** Circle **a try**, run the following code in your Python shell:
 - **Besides** using regular named functions to provide getter methods in your properties, you can also use lambda functions.
 - A decorator in Python is a function that takes another function as its argument, and returns **yet** another function.
 - **The somewhat cryptic output** simply means that the first variable refers to the local first_child() function inside of parent(), while second points to second_child().
 - You **can now use** first and second as if they are regular functions, even though the **functions they point to** can’t beessed directly:
 - However, in this last example, you did not add parentheses to the inner functions—first_child—**upon returning**. Now that you’ve seen that functions are just like any other object in Python, you’re ready to move on and see the magical beast that is the Python decorator. 
 - **That way,** you got a reference to each function that you could call in the future. **Make sense?**
 - **Now that you’ve** seen that functions are just like any other object in Python, **you’re ready to move on** and see the magical beast **that is** the Python decorator. 
 - Let’s **start with** an example:
 - **In effect**, the name say_whee now **points to** the wrapper() inner function. 
 - **So as not to** disturb your neighbors, the following example will only run the decorated code during the day:
 - The way you decorated say_whee() above is a little **clunky**. 
 - **First of all**, you **end up typing** the name say_whee three times. 
 - In addition, the decoration **gets a bit hidden away below** the definition of the function.
 - The following example **does the exact same thing as** the first decorator example:
 
 - Generals warning of a military-industrial complex, product managers who **narc on mendacious management**, and tech leaders who violate **the Silicon Valley code of the white guy** — never criticize each other or your noble missions to save the world.
 - Jack Dorsey **has drawn his sword** and **taken aim at** colleagues **attempting to** centralize control and **gain from the promise of** decentralization. **Specifically,** “web3.”
 - What is web3? It’s a **hazy**/vague term **describing** a crypto-powered internet, and **a font of yogababble**.
 - **Its promoters** would say **something akin to**:
 - Unlike web2 (the current web), which is dominated by centralized platforms such as Google, Apple, and Facebook, web3 will use blockchain, crypto, and NFTs to **transfer power back to** the internet community. 
 - **Sounds good**. Most of us **buy the down-with-Facebook-and-Google narrative**. 
 - **Cut out** the middleman, and we all win — especially the little guys.
 - **The dispersion of** theaters, doctors offices, and bank branches **to** our homes, smart speakers, and phones **offers enormous potential to** provide elemental services **with reduced friction**. 
 - **At an extreme**, if a tree divides houses into only 2 or 4, each group still has a wide variety of houses. 
 - **Resulting predictions** may be **far off** for most houses, even in the training data (and it will be bad in validation too **for the same reason**).
 - There are a few alternatives for controlling the tree depth, and many **allow for some routes** through the tree **to have** greater depth than other routes.
 - But the max_leaf_nodes argument provides a very **sensible way to control** overfitting vs underfitting. 
 - 









 
