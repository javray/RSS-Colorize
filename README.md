# RSS Colorize #

Simple PHP Script thats recieves an RSS and outputs it with SHELL
colors.

## Usage ##

<pre>
curl -s http://www.somthing.com/rss | rss title=this link -10
</pre>

The script accepts any number of parameters whats are tags from RSS. If
a tag have an assert, this means that if the tag contains the text will
show it in the result otherwise don't. The parameter leading minus means
the number of results from the rss.


