---
  title: Contributing
  weight: 10
  render-file: false
---

### Developing

Please avoid making changes to the browser versions of chai if you are developing in the browser. All
changes to the library are to be made to `lib/*` and then packaged for the browser using the `make`
command.

### Testing

Tests are written in `exports` style on [mocha test framework](http://visionmedia.github.com/mocha/).
There is a test file for each of the interfaces. The tests for `expect` and `assert` must pass in node.js
and in the browser, whereas the should tests only need to pass on node.js.

Browsers tests are currently known to pass in Chrome 16 and Firefox 8. Please let me know if you can test
in other browsers or other version.

#### Server Side Testing

It's quite simple...

      make test


#### Browser Side Testing

It's also quite simple. Open up `test/browser/index.html` in your nearest browser.


### Building

If you have made changes to any of the components, you must rebuild the browser package.

      $ make

### Contributors 

     project: chai
     commits: 278
     files  : 71
     authors: 
       211  Jake Luer               75.9%
        53  Veselin Todorov         19.1%
         5  Juliusz Gonera          1.8%
         3  Jeff Barczewski         1.1%
         2  Jo Liss                 0.7%
         1  Vinay Pulim             0.4%
         1  Jakub Nešetřil          0.4%
         1  John Firebaugh          0.4%
         1  Domenic Denicola        0.4%