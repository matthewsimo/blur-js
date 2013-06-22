## Blur-js

Use js to blur images!

### StackBlur Refactored

I saw this demo at `http://www.quasimondo.com/StackBlurForCanvas/StackBlurDemo.html` but noticed that the script used to do the blur could be refactored in a more DRY manner. I've moved the refactored script over to the [refactored-legacy branch](https://github.com/matthewsimo/blur-js/tree/refactored-legacy), take a look over there if you're looking for that.

### Blur-js

Master branch will be dedicated to my implementation which will focus on flexability, ease of use, and maybe some other features I'm kicking around.


#### Running the Demo

To run the demo, after cloning, run `npm install` to get the webserver in place, then run `node node_modules/webserver/webserver.js` from your command line.

After that, visit `http://localhost:8003/demo.html` - (chrome doesn't like running it directly from the file - hence the webserver.)

