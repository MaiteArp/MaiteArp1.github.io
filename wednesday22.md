## Wednesday 22

# Computer Architecture and Logic

[README](./README.md)
[monday](./monday.md)
[wednesday15](./wednesday15.md)
[friday17](./friday17.md)
[saturdayhtml](./saturdayhtml.md)
[saturdaycss](./saturdaycss.md)
[saturdayjs](./saturdayjs.md)
[monday20](./monday20.md)
[learned](./learned.md)


## Videos 

The videos talked about how a computer works. 

It takes  *input* 
          *stores* that input
          *process* using algorythims 
          *output* the processed information

The information a computer works with is *binary data* a collection of 1's and 0's, that are processed in circuts. 
Over time circuts have become smaller and smaller. Which has made them faster and faster. 

## Java Script Loops

* Loops check a condition. If it returns *true* a code block will run 
* This process repeats until it returns *false*
* __For__ loop - it runs a block of code a specific number of times (most common loop)
* For loop condition is usually a counter, which is used to tell how many times the loop should run

```var extraQuestion = prompt('would you want to add more cats?');
console.log (extraQuestion);
while (extraQuestion === 'no') {
  extraQuestion = prompt('what about now?');
}

if (extraQuestion === 'yes') {
  extraQuestion = prompt('how many more?');

  var element = document.getElementById('response');

  for (var i = 0; i < extraQuestion; i++) {
    document.write('<img src="http://placekitten.com/200/300">');
    
  }
} 
```


