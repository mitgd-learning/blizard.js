# blizard.js

> __This library is still in the development stage. It is incomplete but, you are welcome to contribute.__  

## Getting Started

Include the `blizard.js` file in your document the way which you prefer. Something like:  

`<script src="http://blizardjs.ueuo.com/blizard.js"></script>`  

or if you choose to host it yourself:  

`<script src="js/blizard.js"></script>`  
> Remember to replace the location with the location where it resides on your machine/server.

### Usage

***sl.print(@elementId-toChange, @newString);***  

    sl.print(‘p’, ‘Hello’);

<br>  

***sl.hide(@elementId-toHide);***  

    sl.hide(‘p1’);

<br>  

***sl.show(@elementId-toShow);***  

    sl.show(‘p1’);

<br>  

***sl.col(@elementId-toChangeColor, @newColor);***  

    sl.col(‘p1’, ‘red’);

<br>  

***sl.family(@elementId-toChangeFont, @newFontFamily);***  

    sl.family(‘p1’, ‘Impact, Charcoal, sans-serif’)

<br>  

***sl.size(@elementId-toChangeSize, @newSize);***  

    sl.size(‘p1’, ‘medium’);  
> Options for __*size*__:  
> *xx-small  |  x-small  |  small  |  medium  |  large  |  x-large  |  xx-large  |  smaller  |  larger*  

<br>  

***sl.wait(@function, @milliseconds);***  

    sl.wait(‘f1()’, 1000);  
    function f1() {  
      alert(‘i love blizard.js’);  
    };

<br>  

***sl.setlocalstorage(@nameForStorage, @storageValue);***  

    sl.setlocalstorage(‘name’, ‘smith’);

<br>  

***sl.printlocalstorage(@element-toShowValue, @storageToShow);***  

    sl.printlocalstorage(‘p1’, ‘name’);

<br>  

***sl.click(@element-toMakeClickable, @function-whenClicked);***  

    sl.click(‘p’, ‘click()’);
    function click() {
      console.log(‘do something in here’);
    };

<br>  

***sl.id(@element-toChangeId, @element-newId);***  

    sl.id(‘old-id’, ‘new-id’);
> Could be used to modify element styles without additional Javascript.  

<br>  

***sl.createElement(@NEW-ELEMENT, @PARENT, @newElement-id);***  

    sl.createElement(‘P’, ‘HEAD’, ‘id’);
> Use capitals for parameter 1 and parameter 2.

## Built With

* [atomo.css](https://atomo.ueuo.com/) - Simple HTML/CSS library by Rohan Samra-O’Neill

## Authors

* **Rohan Samra-O’Neill** - [Slitherlizard](https://github.com/Slitherlizard/)

See also the list of [contributors](https://github.com/Slitherlizard/blizard.js/blob/master/authors.txt) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Slitherlizard/blizard.js/blob/master/LICENSE) file for details.

## Acknowledgments

* **Ethan Priest** - [allyouaskfor](https://github.com/allyouaskfor/) - Created a proper [README](https://github.com/Slitherlizard/blizard.js/blob/master/README.md)
=======
the brand new javascript library.
# This library is not fully finished and you are welcome to help with it
# blizard.canvas.js is out now to get a tutorial on it go to https://github.com/Slitherlizard/blizard.canvas.js
# tutorial
the code below is the link to the blizard.js library
        `<script src="http://blizardjs.ueuo.com/blizard.js"></script>`
–––––
        with sl.print the first parameter is the id of the element you want to change the second is the text you want to change it to
`sl.print("p", "hi")`
with sl.hide the parameter is the id of the element you want to hide
`sl.hide("p1");`
  with sl.show the parameter is the id of the element you want to show
  `sl.show("p1");`
 with sl.col the first parameter is the id of the element you want to change the color of, the second parameter is the color you want to change it to
` sl.col("p1", "red");`
 with sl.family the first parameter is the id of the element you want to change the font-family of, the second parameter is the font family you want to change it to
` sl.family("p1", "Impact,Charcoal,sans-serif");`
 with sl.size the first parameter is the id of the element you want to change the size of, the second parameter is the size you want to change it to these are the sizes you can use

. xx-small
. x-small
. small
. medium
. large
. x-large
. xx-large
. smaller	
. larger

` sl.size("p1", "medium");`
 
with sl.wait the first parameter is where you call the function you want to run, the second parameter is the amount of milliseconds you want towait to call that function
 `sl.wait("f1()", 1000);
 function f1() {
    alert('i love blizard.js');
 }`
  with sl.setlocalstorage the first parameter is the name of your localstorge item so that you can refer to it later, the second parameter is the value of your item.
`sl.setlocalstorage("name", "smith");`
 with sl.printlocalstorage the second parameter is the name of the localstorge item you want to print the value of, the first parameter is the id of the element you want to print the item's value to.
`sl.printlocalstorage("p1", "name")`
With sl.click the first parameter is the id of the element you would like to add an onclick event to, the second parameter is the function you want to run when that element is clicked.
` sl.click("p", "click()");`
With sl.id the first parameter is the id of the element you want to change the id of, the second parameter is the new id you would like to give that element, this can be used to change styles over time without using javascript.
with sl.createElement() the first parameteris the element you want to create like P be sure to wright it in capital letters and the second parameter is the element you want to append it to the third parameter is the id you would like to give that element
` sl.createElement("P", "HEAD", "id")`
With sl.changeBackgroundColor() the first parameter is the elememt you wish to change the background color of. The second parameter is the 
color you would like to give that element such as "blue" or "red".
# please report any issues you have with the tutorial or just with the library at all and the blizard.js team(me) will fix it to make your experiense with blizard.js better.

