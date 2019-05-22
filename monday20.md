## Monday 20th ## 

# More JS 

[README](./README.md)
[monday](./monday.md)
[wednesday15](./wednesday15.md)
[friday17](./friday17.md)
[saturdayhtml](./saturdayhtml.md)
[saturdaycss](./saturdaycss.md)
[saturdayjs](./saturdayjs.md)
[learned](./learned.md)

## ABC of Programming 

* A script is a series of instructions the computer can follow in order to achieve a goal
* Each time a script runs, it could only be using one subset of instructions 
* Computers approach tasks in a different way. Programmatically. Think a *very* literal 3 year old 
* When writing a script break it down into a series of steps. for each needed part. Flow charts help

## Expressions 

* JS distinguishes between text, numbers, and *boolean* values (true or false)
* Evaluate into a single value 
* Rely on operators to calculate a value 

## Functions 

``` console.log('This is my cat');

var catQuestion = prompt('Do you like cats?');
console.log (catQuestion);

if (catQuestion === 'yes') {
document.write('<h3>Welcome to the cat page!</h3>')
} else if (catQuestion === 'no') {
document.write('<h3>Welcome anyway...</h3>')
} else {
    document.write('<h3>Welcome!</h3>') 
}


function catOrder (catNumber, typeOfCat) {
    var newOrder = 'The ' + catNumber + ' ' + typeOfCat + ' cats are on their way to you';
    var yourCatsHtml = '<p>' + newOrder + '</p>';
    return yourCatsHtml;
}

var catNumber = prompt('How many cats would you like to take home?');
var typeOfCat = prompt('what type of cat is your favorite?');

var order = catOrder(catNumber, typeOfCat);

document.write(order);

// this part was completed with a little help from google and a more experienced programmer

function loaded() {

  var happyWithOrder = prompt('Are you happy with the order?');
  if (happyWithOrder === 'yes') {
    var secondOrder = prompt('how many more cats would you like?');
    if (secondOrder === 'none'|| secondOrder === '0') {
      var lastAnswer = document.getElementById("response");
      lastAnswer.innerText = 'Thank you come again!';
    } else {
      var noMore = document.getElementById("response");
      noMore.innerText = 'Sorry we are out';
    }
  } else if (happyWithOrder === 'no') {
    var cancel = prompt('would you like to cancel the order?');
    if (cancel === 'yes') {
      var cancelOrder = document.getElementById("response");
      cancelOrder.innerText = 'No cats for you';
    }
  }
}

window.onload = loaded ```


