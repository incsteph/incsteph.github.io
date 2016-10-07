---
layout: post
title: "Here, I test all the markdowns!"
date: 2016-10-07 11:41:23 +0800
categories: [markdown, jekyll, test]
tags: [test]
---

Edit: Seems like other people like to do (this)[https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet] too...
And the cheatsheet I referred the below (from)[http://packetlife.net/media/library/16/Markdown.pdf]

## <i>HEADERS</i>

	# This is H1

# This is H1


	## This is H2

## This is H2


	### This is H3

### This is H3


	#### This is H4

#### This is H4


	##### This is H5

##### This is H5


	###### This is H6

###### This is H6


* * *


## <i>LISTS</i>

### unordered

	* Sizes
	* Shapes
	* Colors
		* Blue
		* Orange


* Sizes
* Shapes
* Colors
	* Blue
	* Orange

### ordered

	1. First
	2. Second
	3. Third
		1. Alpha
		2. Bravo

1. First
2. Second
3. Third
	1. Alpha
	2. Bravo


* * *


## <i>BLOCKQUOTES</i>

### separated
	> Lorem ipsum
	> dolor sit amet

> Lorem ipsum
> dolor sit amet  
  


### one line
	> Lorem ipsum dolor
	sit amet

> Lorem ipsum dolor
sit amet
  
  

### nested lines
	> Level one
	>
	> > Level two
	> >
	> > > Level three

> Level one
>
> > Level two
> >
> > > Level three

this does not work

	> Level one
	> > Level two
	> > > Level three

> Level one
> > Level two
> > > Level three

* * *


## <i>INLINE CODE</i>

Use `<div>` tags

``echo `uname -a```


* * *


## <i>CODE BLOCKS</i>

Normal text

	#include <stdio.h>
	<b>this is part of a code block</b>


* * *


## <i>HORIZONTAL RULES</i>

* * *
***
- - -
---


* * *


## <i>EMPHASIS</i>

*Emphasis*

_Emphasis_

**Strong**

__Strong__

*Super*emphasis

**Super**strong


* * *


## <i>ESCAPABLE CHARACTERS</i>

\ Backslash  
` Backtick  
* Asterisk  
_ Underscore  
{ } Curly braces  
[ ] Square brackets  
( ) Parentheses  
# Hash mark  
+ Plus sign  
- Hyphen  
. Period  
! Exclamation  


* * *


## <i>LINKS</i>

[Google](http://google.com/)

[Google](http://google.com/ "Search")

[google]: http://google.com/ "Search"

[Google][google]

<http://google.com>


* * *


## <i>IMAGES</i>

![Alt text](/path/to/img.jpg)

![Alt text](/path/to/img.jpg "Title")

[img1]: /path/to/img.jpg "Title"

![Alt text][img1]