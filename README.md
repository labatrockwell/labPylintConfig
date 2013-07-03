#labPylintConfig
This is our configuration file for [Pylint](http://www.pylint.org/)

We don't want to impose an excessive amount of restrictions on people's code, but there are some things like variable naming conventions and tab vs. space that we want to normalize.

A great part of using a linter is that it does a quick sanity-check on your code before you waste time trying to run it.


##Setup
1. Clone this repo `git clone https://github.com/labatrockwell/labPylintConfig.git`
2. Copy pylintrc to your home driectory `cp pylintrc ~/.pylintrc`
3. Install Pylint `sudo pip install pylint`
4. Sanity-check your code! `pylint mymodule.py`
  * You can check just errors using `pylint -d all -e E mymodule.py`
  * Find out more by running `pylint --help`

###Updating
1. Pull the latest changes `git pull`
2. Copy pylintrc to your home directory `cp pylintrc ~/.pylintrc`
