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
´
alert('hello world')
´

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


Lists
-----

### Unordered Lists
* Listpoint 1
* Listpoint 2
* Listpoint 3

- Listpoint 1
- Listpoint 2
- Listpoint 3

+ Listpoint 1
+ Listpoint 2
+ Listpoint 3

### Ordered Lists
1. Listpoint 1
1. Listpoint 2
1. Listpoint 3

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