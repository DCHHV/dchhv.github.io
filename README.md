DEF CON Hardware Hacking Village
===========================================
This is the main website of the DC HHV, served up right here on github pages using a custom domain.

Building and running locally
-------------
For testing purposes, it's possible to serve up this Jekyll based site on a localhost.  This can be used for previewing content before pushing it to the main repo.  Note that this does use lots of bits of Ruby, so it can get a little ugly to set up.

To install some of the base pre-requisites in Debian/Ubuntu based systems (You may need to modify the installer commands for other distros):

`apt-get install zlib1g-dev bundler`

With the Ruby bundler installed, clone this repository, navigate to it and run:

`bundle install`

Note that it may be necessary to install additional Ruby tools.  If there are any errors be sure to check the output and resolve them before continuing.

At this point, the website can be served up:

`bundler exec jekyll serve`

This will serve an instance of this website at localhost:4000
