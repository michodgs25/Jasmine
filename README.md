# Jasmine testing

## Purpose
The purpose of learning about jasmine testing, is to test the outcome of function. 
First by intentionally failing the code, write enough code for it to pass then refract the code.
Red, Green, refractor method.

## Test example

#### Create calculator object in __scripts/calc.js__

```
Calculator = function() {
    this.value = 0;
}

Calculator.prototype.add = function(number) {
    if(typeof(number) == "number") {
        this.value += number;
    } else {
        alert("Error!");
    }
}
```
####
