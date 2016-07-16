# Writing Tests for Drupal
I am working on improving my ability to write tests for Drupal: particularly for core and contrib development. Rather than just keep notes for myself, I thought I would share the resources I find in this repo so others can learn from this and contribute.

If you have resources you would like to contribute, feel free to fire up a pull request!

## drupal.org documentation
- [Drupal 8 automated testing API docs]: https://api.drupal.org/api/drupal/core%21core.api.php/group/testing
- [PHPUnit guide]: https://www.drupal.org/phpunit
- [SimpleTest guide]: https://www.drupal.org/simpletest
- [Contributor task: write an automated test for a Drupal core bug](https://www.drupal.org/contributor-tasks/write-tests)

## DrupalCon sessions

### 2016
#### New Orleans
- [What type of testing is good for me?](https://events.drupal.org/neworleans2016/sessions/what-type-testing-good-me), Yuriy Gerasimov (ygerasimov): [video](https://www.youtube.com/watch?v=P81DeT921Mk)
- [Behat: Behavior-Driven Development, Functional Tests & Selenium (in Drupal!)](https://events.drupal.org/neworleans2016/sessions/behat-behavior-driven-development-functional-tests-selenium-drupal), Ryan Weaver (weaverryan): [video](https://www.youtube.com/watch?v=nnbpE7s-9J4) and [slides](https://events.drupal.org/sites/default/files/slides/behat3-drupal.pdf)
- [Automated javascript testing: where we are and what we actually want](https://events.drupal.org/neworleans2016/sessions/automated-javascript-testing-where-we-are-and-what-we-actually-want), Daniel Wehner (dawehner): [video](https://www.youtube.com/watch?v=Uf0cc3Nnm_k)

### 2015
#### Barcelona
- [Principles of Solitary Unit Testing](https://events.drupal.org/barcelona2015/sessions/principles-solitary-unit-testing), Joseph Purcell (josephdpurcell): [video](https://www.youtube.com/watch?v=8kzjVG3ts2w)
- [Behat+Mink+PhantomJS = Test ALL THE THINGS!](https://events.drupal.org/barcelona2015/sessions/behatminkphantomjs-test-all-things), Michelle Sanver (michellesanver): [video](https://www.youtube.com/watch?v=cdbhYLeH_ig)
- [Visual Regression Testing](https://events.drupal.org/barcelona2015/sessions/visual-regression-testing-codified-knowledge-base), 
Amitai Burstein (amitaibu): [video](https://www.youtube.com/watch?v=6j6EqmgcM_A)
- [Testing with Monkeys: Using Chaos for Better Code](https://events.drupal.org/barcelona2015/sessions/testing-monkeys-using-chaos-better-code), Andrew Holgate (andrewsuth): [video](https://www.youtube.com/watch?v=W83YhmwFWCk)
- [SmarTest: Proposal for accelerating the detection of faults in Drupal](https://events.drupal.org/barcelona2015/sessions/smartest-proposal-accelerating-detection-faults-drupal), Ana Belén Sánchez (anabsanchez): [video](https://www.youtube.com/watch?v=_QBQkA741LY)

#### Los Angeles
- [CI for CSS: Creating a Visual Regression Testing Workflow](https://events.drupal.org/losangeles2015/sessions/ci-css-creating-visual-regression-testing-workflow), Kate Kligman: [video](https://www.youtube.com/watch?v=D63FWeYhISU) and [slides](https://events.drupal.org/sites/default/files/slides/ci_for_css_kate_kligman.pdf)
- [Using Grunt to Manage Drupal Build and Testing Tools](https://events.drupal.org/losangeles2015/sessions/using-grunt-manage-drupal-build-and-testing-tools), Joe Turgeon (arithmetic): [video](https://www.youtube.com/watch?v=XVydW7dTsCc) and [slides](https://events.drupal.org/sites/default/files/slides/Using%20Grunt%20with%20Drupal.pdf)
- [Test-driven Drupal upgrades](https://events.drupal.org/losangeles2015/sessions/test-driven-drupal-upgrades), Alex Dergachev (dergachev), Dave Vasilevsky (vasi): [video](https://www.youtube.com/watch?v=m7yR3INX7fs)
- [Multidimensional testing workflow before merge to master](https://events.drupal.org/losangeles2015/sessions/multidimensional-testing-workflow-merge-master), Yuriy Gerasimov (ygerasimov), Andrii Podanenko (podarok): [video](https://www.youtube.com/watch?v=o0pqKqnhWgw) and [slides](https://events.drupal.org/sites/default/files/slides/DrupalCon%20presentation%20CIBox.pdf)

### 2014
#### Amsterdam
- [The Future of Drupal Functional Testing](https://amsterdam2014.drupal.org/session/future-drupal-functional-testing.html), Nick Schuch (nick_schuch), Cameron Zemek (grom358), Lee Rowlands (larowlan), Konstantin Kudryashov (everzet): [video](https://www.youtube.com/watch?v=ZaBvq8YlLm0)
- [Doing Behaviour-Drive Development with Behat](https://amsterdam2014.drupal.org/session/doing-behaviour-driven-development-behat.html), Konstantin Kudryashov (everzet): [video](https://www.youtube.com/watch?v=lfW2ngf5DgE)
- [Automated Frontend Testing](https://amsterdam2014.drupal.org/session/automated-frontend-testing.html), Chris Ruppel (rupl): [video](https://www.youtube.com/watch?v=qhA6O1u97PE)

#### Austin
- [From User Personas to Testing: A Project Manager's Journey to Behat](https://austin2014.drupal.org/session/user-personas-testing-project-managers-journey-towards-behat.html), Michelle Lauer (miche): [video](https://www.youtube.com/watch?v=V7IlmMoAZf4)
- [Browser Eyeballing != JavaScript Testing](https://austin2014.drupal.org/session/browser-eyeballing-javascript-testing.html), Jordan Kasper (jakerella): [video](https://www.youtube.com/watch?v=xO2vtmrfReA)
- [Automated Frontend Testing](https://austin2014.drupal.org/session/automated-frontend-testing.html), Chris Ruppel (rupl): [video](https://www.youtube.com/watch?v=1PCdlBSKhKk)

### 2013
#### Prague
- [Leveraging 12 years of PHP Unit](https://prague2013.drupal.org/session/leveraging-12-years-phpunit.html), Sebastian Bergmann: [video](https://www.youtube.com/watch?v=AXZ1I5M6sHQ)
- [Writing Unit Testable Code in Drupal 8](https://prague2013.drupal.org/session/writing-unit-testable-code-drupal-8.html), Mark Sonnabaum (msonnabaum): [video](https://www.youtube.com/watch?v=dMxSMPNu094)
- [JavaScript Testing](https://prague2013.drupal.org/session/javascript-testing.html), Théodore Biadala (nod_), Jesse Beach, Steve De Jonghe (Seutje): [video](https://www.youtube.com/watch?v=IrqEBNoXvR4) and [slides](https://docs.google.com/presentation/d/1ZHVbnaHxv5lCzekeFXIgUNg-N5gqX7Wn-gZhAgdTZ-c/edit)
- [Automated Acceptance Tests with Behat](https://prague2013.drupal.org/session/automated-acceptance-tests-behat.html), Nathan Lisgo (nlisgo): [video](https://www.youtube.com/watch?v=pMvW2IK8Hl0)
- [Behat + Contrib](https://prague2013.drupal.org/session/behat-contrib.html), Melissa Anderson (eliza411), Howard Tyson (tizzo), Sam Boyer (sdboyer), Graham Taylor (tayzlor): [video](https://www.youtube.com/watch?v=2jL-cnwxqdo)
- [Selenium/Webdriver: What, Where, Why and How](https://prague2013.drupal.org/session/selenium-webdriver-what-where-why-and-how.html), Earnest Berry (souvent22): [video](https://www.youtube.com/watch?v=ZvBuX0VsDXQ)

#### Portland
- [Behat, Behavior-Driven Development and Selenium in Drupal](https://portland2013.drupal.org/session/behat-behavioral-driven-development-and-selenium-drupal.html), Ryan Weaver (weaverryan): [video](https://www.youtube.com/watch?v=b_35hrRSVog)
- [Automated Testing with Jasmine and PhantomJS](https://portland2013.drupal.org/session/automated-testing-jasmine-and-phantomjs.html), Ronn Abueg (ronnbot) and Aisha Kaliel (akaliel): [video](https://www.youtube.com/watch?v=p5w6oNFT4ks)
- [Testing your Drupal infrastructure](https://portland2013.drupal.org/session/testing-your-drupal-infrastructure.html), Barry Jaspan (bjaspan): [video](http://youtu.be/EHztJaDrAPo)

#### Sydney
- [Show me the tests! Writing automated tests for Drupal](https://sydney2013.drupal.org/show-me-tests-writing-automated-tests-drupal), Lee Rowlands (larowlan): [slides](https://sydney2013.drupal.org/sites/default/files/slides/Drupalcon%20Sydney%20-%20Show%20me%20the%20tests!%20Writing%20Automated%20Tests%20for%20Drupal.pdf)

### 2011
#### Chicago
- [Automated Testing and Drupal](https://chicago2011.drupal.org/sessions/automated-testing-and-drupal), Steven W. Merrill: [video](https://archive.org/details/drupalconchi_day2_automated_testing_and_drupal)

### 2010
#### Copenhagen
- [Use SimpleTest!](https://cph2010.drupal.org/sessions/use-simpletest.html), Karsten Frohwein: no slides or video

### 2009
#### Paris
- [Introduction to testing with Drupal: SimpleTest](http://paris2009.drupalcon.org/session/introduction-testing-drupal-simpletest.html), Jimmy Berry (boombatower): no slides or video

#### Washington, DC
- [Intro to SimpleTest](http://dc2009.drupalcon.org/session/intro-simpletest.html), Florian Loretan (flobruit): video on session page

### 2008
#### Szeged
- [Testing, part 1: Intro to testing](http://szeged2008.drupalcon.org/program/sessions/testing-part-1-intro-testing.html), Angie Byron (webchick) and Florian Loretan (flobruit): [video](https://archive.org/details/testing_part_1) and [slides](http://szeged2008.drupalcon.org/files/Simpletest-szeged.pdf)
- [Testing, part 2: Awesome testing party!](http://szeged2008.drupalcon.org/program/sessions/testing-part-2-awesome-testing-party.html), Angie Byron (webchick) and the Drupal Testing Brigade: [video](http://www.archive.org/details/testing_part_2)
- [What is SimpleTest? and SimpleTest Automator: Automated Automated Testing](http://szeged2008.drupalcon.org/program/sessions/what-simpletest-and-simpletest-automator-automated-automated-testing.html), Charlie Gordon (cwgordon7): no slides or video

#### Boston
- [SimpleTest: Because clicking on forms is for suckers](http://boston2008.drupalcon.org/session/simpletest-because-clicking-forms-suckers.html), Angie Byron (webchick), Rok Zlender, Karoly Negyesi (chx), Jimmy Berry (boombatower): resource list on session page 

# Articles
- [Write Unit Tests for Your Drupal 7 Code, Part 1](https://www.lullabot.com/articles/write-unit-tests-for-your-drupal-7-code-part-1), Mateu Aguiló Bosch (e0ipso), lullabot.com, August 5, 2015
- [Write Unit Tests for Your Drupal 7 Code, Part 2](https://www.lullabot.com/articles/write-unit-tests-for-your-drupal-7-code-part-2), Mateu Aguiló Bosch (e0ipso), lullabot.com, August 10, 2015
- [Automated Testing of Drupal 8 Modules](https://www.sitepoint.com/automated-testing-drupal-8-modules/), Daniel Sipos, sitepoint.com, May 1, 2015
- [CSS Regression Testing with Resemble.js](https://www.lullabot.com/articles/css-regression-testing-with-resemblejs), Blake Hall, lullabot.com, June 25, 2014
- [Write testable code in Drupal - part 3, practical expamples](http://wadmiraal.net/lore/2014/07/24/write-testable-code-in-drupal-part-3/), Wouter Admiraal, wadmiraal.net, July 24, 2014
- [Write testable code in Drupal - part 2, purity is the answer](http://wadmiraal.net/lore/2014/07/23/write-testable-code-in-drupal-part-2/), Wouter Admiraal, wadmiraal.net, July 23, 2014
- [Write testable code in Drupal - part 1, what is wrong with Drupal tests](http://wadmiraal.net/lore/2014/07/22/write-testable-code-in-drupal-part-1/), Wouter Admiraal, wadmiraal.net, July 22, 2014
- [Testing the front end with CasperJS](https://www.lullabot.com/articles/testing-the-front-end-with-casperjs), Juampy NR, lullabot.com, March 12, 2014
- [3 Easy Steps to Drupal Unit Tests](https://www.phase2technology.com/blog/3-easy-steps-to-drupal-unit-tests/), Erik Summerfield, phase2technology.com, October 2, 2012
- [Writing automated tests in Drupal 7](http://blog.worldempire.ch/story/writing-automated-tests-drupal-7), Sascha Grossenbacher (berdir), March 11, 2010
- [A Drupal Module Developer's Guide to SimpleTest](https://www.lullabot.com/articles/an-introduction-to-unit-testing-in-drupal), https://www.lullabot.com/articles/a-drupal-module-developers-guide-to-simpletest, lullabot.com, January 1, 2008
- [An Introduction to Unit Testing in Drupal](https://www.lullabot.com/articles/an-introduction-to-unit-testing-in-drupal), Angie Byron, lullabot.com, November 26, 2007

# Video tutorials
- [Automated Testing in Drupal 7 with SimpleTest](https://drupalize.me/videos/introduction-automated-testing-simpletest?p=1881), drupalize.me series
