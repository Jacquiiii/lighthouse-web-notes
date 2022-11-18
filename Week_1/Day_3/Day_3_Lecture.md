## Day 3 Lecture Notes: Nov 16, 2022

* FYIs:
    * Number. MAX_SAFE_INTEGER gets the max size of an integer that JS can understand
    * To create a bigInt, add an n at the end
    * Primative data types are not mutable. When changing a value, think of it as throwing away the old value and adding in a new value.
    * Literals
        * [] = array literal
        * {} = object literal
        * Think of this like literally create this
    * To comment out a bunch of lines highlight them then ctrl-/
        * If you use ctrl/ on commented lines, it removes it
    * Anything on the right side of an = is a value
* Objects:
    * Objects are a collection of key value pairs
    * In other programming languages they are referred to in different names (e.g. ruby it’s called hash)
    * Think of keys like the objects index/position
    * To add to object: obj[‘key’] = value;
    * To change an obj: obj[‘key’] = value;
    * Dot notation:
        * Can use . Syntax as well: obj.key (no need to make the key a string like in bracket notation)
        * Can’t use it with a variable
        * Better for readability
    * Objects are passed by reference, you give the original object to the function
    * Functions:
        * Functions are objects so when you say the function name you are just getting the function name back and not the output of the actual function
        * Can define in or out of the function. Don’t make reference to things outside of the object {}
        * this:
            * variable that can be used inside of a function to reference the object and fixes any bugs related to object name change or copies. 
            * Works in nested objects too, always refers to the object in which the function is.
            * Way to think of it: my object aka referring to the object it’s inside when written
    * Looping:
        * Use for..in loop to loop through an object
        * Syntax: 
            * for (let key in object) {return key} will give you keys
            * for (let key in object) {return object[key]} will give you values
            * for (let key in object) {return object[key][index]} will give you value of an array index if value is array
            * Object.keys or object.value
                * think of Object.keys as giving you a ‘table of contents’ for the object

### Links

* [Code demo & notes](https://github.com/andydlindsay/telus-nov14-2022/tree/master/w01d03)
* [Lecture recording](https://us02web.zoom.us/rec/play/qYl69imnuLH9v6guZkA7H2TSpXsCoatlbp8eZioiXxHzRNJEspbk7MQllySHBhIHK4YIeRtYGR9TB28k.l6GnWmCdfsnyJDzP?startTime=1668621240000&_x_zm_rtaid=bEffGVtJQw-Cwa5Z4DBGKw.1668736875233.cb39adb5f243287f4153f8b5f0b33be0&_x_zm_rhtaid=260)


