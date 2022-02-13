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

 
