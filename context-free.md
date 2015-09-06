# Context Free

##  Who is this programming language for?
This language is for artists who are tech savvy or programming inclined. Target markets include artists that want to dabble in tech and techies that want to dabble in art.


## What is easy to do in this language? Why is it easy?
Its easy to draw shapes. There is a lot of built in infrastructure to create shapes of all kinds, sizes and colors in only a few (1 to 5) lines of code. You can do recursion relatively easily and make pictures that are made up of many shapes because of the way that you are able to manipulate the x and y coordinates.


## What is hard to do in this language? Why is it hard?
I found it difficult to manage the colors in context-free. It might have just been me but I found the color commands to be really finicky. In a more macro sense I found it quite difficult to draw things that are either very detailed or made up of shapes that are very curvy. The first was caused by the fact that trying to draw things on a small scale was difficult and understanding the ways in which the rules go together was confusing to me. Also the curviness of shapes that aren't built in to the Context Free grammar is difficult because it reqiures the programmer to use math to create the shapes manually.


## How did you learn how to program in this language?
I read the documentation on archive.org and also looked on forums for examples of successful and interesting code. I moved around other people's code until i figured out what all the parameters did which really helped me get a grip on how it all worked. For me, the practical code examples I could find online were more helpful than the documentation. Also the built in examples were helpful.


## What is the underlying _computational model_ for this programming language? 
_We don't yet have a great definition of the term "computational model". 
For now, try to come up with the clearest, most concise explanation of what 
happens when a ContextFree program runs._
The CFDG is parsed rule by rule starting with the specified start shape. Each command is translated to C++ (or objective-C) and then rendered as shapes that are drawn (i think) by points being moved around and marking the trail. This is a really bad explanation but I am having a hard time thinking of a better one.



## What do you think is interesting about the ContextFree program you wrote?
I think that the use of recursion is really interesting. The way that the x,y-adjustments change only a tiny bit (~.5%) but then come together to create an image is awesome. I also love symmetry in graphic design so I think thats interesting as well.


