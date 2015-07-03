# Performance Metrics

Performance measurement on some of our websites using [sitespeed.io](http://sitespeed.io)

## Usage

First you have to install the tools :

````bash
$ npm install -g phantomjs sitespeed.io
````

Then add or use the text files inside the `sites` directory with the command :

One site check :

````bash
sitespeed.io --sites mysite.txt
````

Many (for comparison) :

````bash
sitespeed.io --sites mysite1.txt --sites mysite2.txt --sites mysite3.txt
````

More information about sitespeed configuration on the [doc](http://www.sitespeed.io/documentation/)

## Deploy

Just push the gh-pages
