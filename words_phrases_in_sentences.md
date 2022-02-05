 - str.join() **takes us in the other direction**, **sewing** a list of strings **up into** one long string, using the string it was called on as a separator.  
 - If we want to **throw in** any non-string objects, we have to be careful to call str() on them first.
 - We call .format() on a "format string", **where** the Python values we want to insert are represented with {} placeholders.
 - Notice how we didn't **even** have to call str() to convert position from an int. 
 - format() **takes care of that for** us.
 - **If that was all that** format() **did**, it **would still be** incredibly useful.
 - But **as it turns out**, it can do a lot more. **Here's just a taste**:

 

 
