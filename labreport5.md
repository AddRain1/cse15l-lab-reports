# **Lab Report 5**
## Part 1
### Student Post

I'm having trouble debugging ListExamples.java. My test cases keep failing because of an out of bounds error and I'm not sure why, but I think it might be because my while loop should check for when the index is less than the length of the list - 1.

### TA Response

Hi! Since the error produced is caused by an index out of bounds, the count of your index is incrementing too high. At the bottom of your code, there are two while loops that iterate while the index is less than or equal to the length of the list. Removing the equal sign should fix this.

