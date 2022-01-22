# auto-anchors
Quick sketch for replacing keywords with anchors linking to their relevant pages, kinda Wikipedia style.

anchors link to ```{keyword}.html``` by default

# screenshot:
![demo](https://user-images.githubusercontent.com/85326346/150629903-7752b0ef-e433-465c-a168-b26c2a12eaea.png)

# useage

to add more/custom keywords:

* add new class styling as you like, name new classes "link"+{id}
* at the bottom, give the functions a word to replace, ```x```, and class id, ```y```

# improve this 

instead of calling addlinks() multiple times, take apart the function and make a forEach loop so you can simply pass an array of keywords.
