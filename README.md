#Whitewidow
Whitewidow is an open source automated SQL vulnerability scanner, that is capable of running through a file list, or can
scrape Google for potential vulnerable websites

#Screenshots
![Alt text](http://s30.postimg.org/7ik6ycicx/githubpic.jpg "Credits, legal, TOS")
![Alt text](http://s30.postimg.org/lstr9typd/githubpic2.jpg "Default Mode")
![Alt text](http://s30.postimg.org/5tb3qa2nl/githubpic3.jpg "File Mode")

#Download
Preferably clone repository, alternatively you can download zip and tarball [here](https://github.com/Ekultek/whitewidow/releases/tag/1.0.6)

#Usage
`ruby whitewidow.rb -h` Will print the help page

`ruby whitewidow.rb -e` Will print the examples page

`ruby whitewidow.rb -f <path/to/file>` Will run Whitewidow through a file

#Dependencies
`gem 'mechanize'`

`gem 'nokogiri', '~> 1.6.7.2'`

`gem 'rest-client'`

`gem 'colored'`

To install all gem dependencies, follow the following template:

`cd whitewidow`

`bundle install`

This should install all gems needed, and will allow you to run the program without trouble.

#Misc
Being an open source project, feel free to contribute your ideas and open pull request. You can fork it clone it do pretty
much whatever you want to do with it. For more information including copyright info please see the docs.

If you decide
to contribute to this project, your name will go in the docs under the author and credits file. It will remain there to
show that you have successfully contributed to Whitewidow. Thank you ahead of time for all contributions

Current Version 1.0.6
