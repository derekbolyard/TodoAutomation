# TodoAutomation

# Requirements:
* Your favorite IDE
** Visual Studio Code, Atom or your pick of Jetbrains products (Webstorm or Intellij recommended if going this route)

* Node and NPM

* Java 11 or greater

* Optional:
** If you wish to follow the Selenium hands-on examples using Python, Python 3.7 is necessary.  
** If using IDE that generates virtualenv automatically, use that.  If not, on Mac, brew install pipenv.  If on Windows, pip install pipenv.

# Setup Instructions
* Clone repo https://github.com/clymerrm/TodoAutomation and run npm install
* Inside of cloned repo, run npm install
* Optional: If using Python, inside of cloned repo, run pipenv install

# Locators
CSS Examples - https://saucelabs.com/resources/articles/selenium-tips-css-selectors

XPATH Examples - https://www.lambdatest.com/blog/complete-guide-for-using-xpath-in-selenium-with-examples/

# Running Javascript Tests from Command Line
* Non-Mocha framework ```node basicTest.spec.js```
* Mocha ```mocha basicTest.spec.js --timeout 10000```

# Node Webdriver-Manager
Need a specific version of chrome driver:

```webdriver-manager update --versions.chrome=78.0.3904.105 --gecko false```
```webdriver-manager start --versions.chrome=78.0.3904.105```
