SeleniumTests
=============

These are a suite of basic end-to-end tests we use on the 
[Stanford OpenEdX Instance][c] to make sure it is healthy and happy.
Especially useful after we do an install.


# How To Use

To run these, you'll need to install the Selenium IDE firefox extension.  

Once you've done that, open a firefox window pointing to class.stanford.edu, then open the Selenium IDE from the "Tools" firefox menu (make sure to use Selenium IDE in popup mode...), and then choose "open test suite...", and open the file "class.stanford.edu.html".

Hit the green triangle whose hover message is "play entire test suite".

To run in Staging, you'll want to point your main firefox window to staging, and get past the basic auth, then open the (same) test suite, and change the "base url" to our staging url - then it should just work to run.
FYI: move the speed slider in the Selenium IDE to midway between fast and slow when running on stage.


# FAQ

### Q: I changed the base URL and it didn't seem to "stick"

For our instance, this would be typing in the "base URL" box to go
from ```class.stanford.edu``` to ```studio.class.stanford.edu```.

A: This seems to be a bug in the Selenium IDE.  The workaround is to
quit out of the IDE and then bring up when you're already pointed at
[staging][s].  


  [c]: https://class.stanford.edu/
  [s]: https://stage.class.stanford.edu/

