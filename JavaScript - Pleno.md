Pergunta 1/14:
Which of the following descriptions best describes the code below?
```html
<script>
var variable1 = {
fastFood: “spaghetti”,
length: 10
};
Object.freeze(variable1);
variable1.price = 50;
delete variable1.length;
</script>
```
- [ ] Object is frozen, a property named “price” is added in the variable1 object, a property named “length” is deleted from this object. At the end of the code, the object “variable1” contains 2 properties.
- [ ] Object is frozen, a property named “price” is not added in the variable1 object, a property named “length” is deleted from this object. At the end of the code, object “variable1” contains 1 properties.
- [ ] Object is frozen, a property named “price” is added in the variable1 object, a property named “length” is not deleted from this object. At the end of the code, object “variable1” contains 1 properties.
- [x] Object is frozen, a property named “price” is not added in the variable1 object, a property named “length” is not deleted from this object. At the end of the code, object “variable1” contains 2 properties.

Pergunta 2/14:
Which of the following will change the image to
companylogo2.gif when the page loads?
Consider the following image definition:
```html
<img id=”logo” src=”companylogo1.gif” height=”12′′ width=”12′′ >
```

- [ ] `document.getElementById(‘logo’).src=”companylogo1.gif”`
- [x] `document.getElementById(‘logo’).src=”companylogo2.gif”`
- [ ] `logo.source=”companylogo2.gif”`
- [ ] `logo.source=”companylogo1.gif”`


Pergunta 3/14:
Which of the following will run the function when a user opens the page?
Consider the following  alert:
```html
<script type=”text/”>
function message() { alert(“Welcome to ExpertRating!!!”) }
</script>
```

- [x] `body onload=”message()”`
- [ ] `body onsubmit=”message()”`
- [ ] `body onreset=”message()”`
- [ ] `body onunload=”message()”`

Pergunta 4/14:
Performance-wise, which is the fastest way of repeating a string in javascript?

- [ ]
```js
    String.prototype.repeat = function(count) {
    if (count < 1) return”;
    var result = ”,
    pattern = this.valueOf();
    while (count > 0) {
    if (count & 1) result += pattern;
    count >>= 1, pattern += pattern;
    }
    return result;
    };
```
- [x]
```js
    String.prototype.repeat = function(num) {
    return new Array(num + 1).join(this);
    }
   ```
- [ ]
```js
        function repeat(pattern, count) {
        if (count < 1) return”;
        var result = ”;
        while (count > 0) {
        if (count & 1) result += pattern;
        count >>= 1, pattern += pattern;
        }
        return result;
        }
```
- [ ]
```js
    String.prototype.repeat = function(n, d) {
    return– n ? this + (d || ”) + this.repeat(n, d) : ”+this
    };
```

Pergunta 5/14:
Which of following uses the “with” statement in  correctly?

- [ ]
```js
    with(document.getElementById(“blah”).style) {
    background = “black”;
    color = “blue”;
    border = “1 px solid green”;
    }
```

- [ ]
```js
    with document.getElementById(“blah”).style background = “black”;
    color = “blue”;
    border = “1 px solid green”;
    End With
```

- [ ]
```js
    with(document.getElementById(“blah”).style) {
    .background = “black”;
    .color = “blue”;
    .border = “1 px solid green”;
    }
```

- [ ]
```js
    with(document.getElementById(“#blah”).style) {
    .background = “black”;
    .color = “blue”;
    .border = “1 px solid green”;
    }
```

Pergunta 6/14:
What will be the final value of the variable “apt”?
```js
var apt=2;
apt=apt<<2;
```
- [ ] `4`
- [x] `8`
- [ ] `16`
- [ ] `2`
- [ ] `6`

Pergunta 7/14:
Having an array object var arr = new Array(), what is the best way to add a new item to the end of an array?
- [ ] `arr.unshift(“New Item”)`
- [ ] `arr.append(“New Item”)`
- [ ] `arr[arr.length] = “New Item”`
- [x] `arr.push(“New Item”)`

Pergunta 8/14:
Which of the following code snippets gets an image’s dimensions (height & width) correctly?

- [ ]
```js
    var img = document.getElementById(“imageid”);
    var width = img.offsetWidth;
    var height = img.offsetHeight;
```

- [x]
```js
    var img = document.getElementById(‘imageid’);
    var width = img.clientWidth;
    var height = img.clientHeight;
```

- [ ]
```js
    var img = document.getElementById(‘imageid’);
    var width = img.getAttribute(‘width’);
    var height = img.getAttribute(‘height’);
```
 
- [ ]
```js
    var img = document.getElementById(‘imageid’);
    var width = img.width;
    var height = img.height;
```

Pergunta 9/14:
Which of the following are correct values of variable `C`, and why?
```html
<script>
variableA = [6, 8];
variableB = [7, 9];
variableC = variableA + variableB;
</script>
```

- [ ] 6, 7, 8 and 9. The + operator is defined for arrays, and it concatenates strings, so it converts the arrays to strings.
- [ ] 6, 15 and 9. The + operator is defined for arrays, and it concatenates numbers, so it converts the arrays to numbers. 
- [ ] 6, 8, 7 and 9. The + operator is defined for arrays, and it concatenates strings, so it converts the arrays to strings.
- [x] 6, 87 and 9. The + operator is not defined for arrays, and it concatenates strings, so it converts the arrays to strings. 

Pergunta 10/14:
Which of the following code(s) produces the following output?
```js
var profits=2489.8237
output : 2489.824
```

- [ ] `profits.formatDollar(3)`
- [x] `profits.toFixed(3)`
- [ ] `profits.nuberFormat(3)`
- [ ] `profits.toFixed(4)`

Pergunta 11/14:
Which of the following correctly sets a class for an element?

- [ ] `document.getElementById(elementId).className = "Someclass";`
- [ ] `document.getElementById(elementId).class = "Someclass";`
- [ ] `document.getElementById(elementId).style = “Someclass”;`
- [x] `document.getElementById(elementId).setAttribute("className", "Someclass");`

Pergunta 12/14:
Which of the following Array methods in runs a function on every item in the Array and collects the result from previous calls, but in reverse?
- [ ] `reduce()`
- [ ] `pop()`
- [ ] `reverse()`
- [x] `reduceRight()`

Pergunta 13/14:
Analyze the following code snippet which uses a Regular Expression character set. What will be the output of this code?
```html
<html>
<body>
<script type=”text/”>
var str = “Is this enough ? ”;
var patt1 = new RegExp(“[^A-J]”);
var result = str.match(patt1);
document.write(result);
</script>
</body>
</html>
```
- [x] `s`
- [ ] `I,s,`
- [ ] `Is`
- [ ] `I`

Pergunta 14/14:
What is the final value of the variable bar in the following code?
```js
var foo = 9;
var bar = 5;
(function() {
var foo = 2;
bar = 1;
}())
bar = bar + foo;
```

- [ ] `14`
- [ ] `3`
- [x] `10`
- [ ] `7`
