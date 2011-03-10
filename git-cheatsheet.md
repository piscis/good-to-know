Github markdown Cheatsheet
==========================

Headlines
---------

# This is an H1
## This is an H2
### This is an H3
#### This is an H4
##### This is an H5
###### This is an H6



Tables
------

 Left align | Right align | Center align 
:-----------|------------:|:------------:
 This       |        This |     This     
 column     |      column |    column    
 will       |        will |     will     
 be         |          be |      be      
 left       |       right |    center    
 aligned    |     aligned |   aligned   


Code-Blocks
------------

### Codeblock - one line 

Use the `printf()` function.

A backtick-delimited string in a code span: `` `foo` ``


### Codeblock - multiple lines 

    var rpc = new easyXDM.Rpc({
        remote: "http://path.to/provider/" // the path to the provider
    }, 
    {
        local: {
            helloWorld: function(successFn, errorFn){
                // here we expose a simple method with no arguments
                // if we want to return a response, we can use `return ....`,
                // or we can use the provided callbacks if the operation is async
                // or an error occurred
            }
        },
        remote: {
            helloWorld:{
                // here we tell the Rpc object to stub a method helloWorld for us
            }
        }
    });


Blockquotes
-----------

### Simple blockquotes
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.


### Nested blockquotes

> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.

### Containing blockquotes

> ## This is a header.
> 
> 1.   This is the first list item.
> 2.   This is the second list item.
> 
> Here's some example code:
> 
>     return shell_exec("echo $input | $markdown_script");


Lists
-----

### Unordered Lists
* Listpoint 1
- Listpoint 2
+ Listpoint 3


### Ordered Lists
1. Listpoint 1
1. Listpoint 2
1. Listpoint 3


### List Examples

#### Intended list
*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
    Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
    viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
    Suspendisse id sem consectetuer libero luctus adipiscing.

#### Paragraph list
*   Bird

*   Magic

#### Blockquote list
*   A list item with a blockquote:

    > This is a blockquote
    > inside a list item.

##### Codeblock list
*   A list item with a code block:

        <code goes here>

##### False Positive example
1986. This is a list.

1986\. That's not a list.


Code Blocks
-----------

Here is an example of AppleScript:

    tell application "Foo"
        beep
    end tell

HTML Encoding example

	<div class="footer">
		&copy; 2004 Foo Corporation
	</div>


## Horizontal rules

* * *

***

*****

- - -

---------------------------------------


## Links

### standard links

This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.

### Links by reference 
I get 10 times more traffic from [Google] [1] than from
[Yahoo] [2] or [MSN] [3].

  [1]: http://google.com/        "Google"
  [2]: http://search.yahoo.com/  "Yahoo Search"
  [3]: http://search.msn.com/    "MSN Search"

### Links by implicit linking
I get 10 times more traffic from [Google][] than from
[Yahoo][] or [MSN][].

  [google]: http://google.com/        "Google"
  [yahoo]:  http://search.yahoo.com/  "Yahoo Search"
  [msn]:    http://search.msn.com/    "MSN Search"


## Emphasis

### Italic
*single asterisks*

_single underscores_

un*frigging*believable

### Bold
**double asterisks**

__double underscores__

un**frigging**believable