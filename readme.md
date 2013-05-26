### StackBlur Refactored

I saw this demo at `http://www.quasimondo.com/StackBlurForCanvas/StackBlurDemo.html` but noticed that the script used to do the blur could be refactored in a more DRY manner.

I'll eventually turn this into an easier to use module namespaced out so it doesn't potentially cause any conflict errors.


All credit should go to the original author. Mario Klingemann -  @quasimondo


To run this, after cloning run `npm install` to get the webserver in place, then run `node node_modules/webserver/webserver.js`.

Then, visit `http://localhost:8003/StackBlur.html` - (chrome won't handle it properly if running directly from the file - hence the webserver.)

