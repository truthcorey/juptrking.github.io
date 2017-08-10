CTS
===================

CTS website

Requirements
------------

In order to run and develop the blog, you'll need [Jekyll](http://jekyllrb.com/) gem installed and [Node](http://nodejs.org/) with [Gulp](http://gulpjs.com/) task manager for compiling/watching styles.

Installation
------------

### Install Ruby 2.1 

    \curl -sSL https://get.rvm.io | bash
    rvm install 2.1
    rvm use 2.1

Note: if you get an error on `rvm use 2.1` then close your terminal window and open a new one.

### Install [Jekyll](http://jekyllrb.com/)

    gem install jekyll

### Install Node.js

You will need to have [homebrew](http://brew.sh/) installed before running this command

    brew install node

### Install [Gulp](http://gulpjs.com/) as global task manager

    npm install -g gulp

### Install the project node depedencies

cd to the root of the repository and run the following:

    npm install

Running Jekyll server
---------------------

    jekyll serve --watch

Development
-----------

Once you have all the things configured, is pretty easy to develop the blog. In order to watch or compile your LESS files you have to run the next command into the repo

    gulp watch #or just 'gulp styles' to compile them

