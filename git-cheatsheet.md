Github markdown Cheatsheet
==========================

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
------

