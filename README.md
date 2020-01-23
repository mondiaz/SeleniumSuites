# SeleniumTestsCopy
This shows test cases and suites created to QA an online learning platform prior to and following code releases.

SeleniumTests
=============

This repository contains a couple of suites of end-to-end tests that my team and I used on the [Stanford OpenEdX Instance][c]([secondary link for historical reference][d]) to make sure it is healthy and happy.
Especially useful after we do an install.


# How To Use

To run these, you'll need to install the Selenium IDE extension for Chrome or Firefox, or both.  

Once you've done that, open a Firefox or Chrome window pointing to lagunita.stanford.edu, then click the Selenium IDE icon in the browser. Select "Open an existing project", and open the file "QA_for_OpenEdX_LMS_suite.side".

Hit the play button with three dashes beside it to run the entire suite.

To run in Staging, you'll want to point your main window to the staging environment and get past the basic auth. Open the (same) test suite, and change the "base url" to our staging url - then it should just work to run.


# Resources used along the way, possibly helpful now

https://selenium.dev/selenium-ide/

https://chrome.google.com/webstore/detail/selenium-ide/mooikfkahbdckldjjndioackbalphokd

https://github.com/SeleniumHQ/selenium/issues

https://saucelabs.com/resources/articles/selenium-tips-css-selectors

http://sqaforums.com/forums/forum.php

https://demo.lagunita.stanford.edu/

https://lagunita.stanford.edu/courses/course-v1:sandbox+qaOpenEdX+Demo/about

https://lagunita.stanford.edu/courses/course-v1:sandbox+qaOpenEdX+FragileCourses/about

 [c]: https://lagunita.stanford.edu/
 [d]: https://web.archive.org/web/20190313144521/https://lagunita.stanford.edu/
