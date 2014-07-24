###Install Xcode for the command line tools first - all of this is dependent.

Make sure you have ruby installed.
Installing with Homebrew and Rbenv is recommended

Here: http://brew.sh/
and
Here: https://github.com/sstephenson/rbenv#homebrew-on-mac-os-x

Trust me, these 

Then you can just use the command 

```
        rbenv install 2.1.whateverversion
```

The basic guide is here:

http://andycroll.com/2014/01/19/serving-a-jekyll-blog-using-heroku/

Though I've added the shotgun gem for local development and kramdown to parse markdown for Heroku.

####If you add a gem / ruby version / command line tool, don't forget to:

### rbenv rehash

this will fix ```many things```