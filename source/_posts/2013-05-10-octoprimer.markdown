---
layout: post  
title: "A Text Sampler"  
date: 2013-05-10 23:03  
comments: true  
external-url:  
categories: [test]  
---


This a Octopress blog entry sampler. All types of content that might find its way into a blog post, to include spiffy plug-in output such as code blocks, blockquotes, and images will be represented. While we're at it: *here is some emphasized text* and might want to check **strong text** as well. Blog posts usually contain links, so here is [an example][1].

A standard Markdown blockquote (George Orwell):

> People sleep peaceably in their beds at night only because rough men stand ready to do violence on their behalf.

And a Octo-powered quote from a written work:

{% blockquote John le Carré, Tinker Tailor Soldier Spy %}
...in the hands of politicians grand designs achieve nothing but new forms of the old misery...
{% endblockquote %} 

The Octopress blockquote plugin also handles tweets [^1]:

{% blockquote @iowahawkblog https://twitter.com/iowahawkblog/status/301462708287598592 %}
Modest proposal: every time one side in Congress introduces legislation, the other side gets to name it.
{% endblockquote %}


## An H2 Header ##
  
### H3 Headers Are Useful ###

#### What About an H4? ####

##### A Fifth Level Header Could Be Useful #####

###### Not Sure About Going All the Way to Six... ######


A sampling of some lists:

1. The first item in an ordered list
2. And the second
3. Good things happen in threes

Another one:

- Unordered list, item the first
- Second is the first loser
- The always important third item.

Here is a basic Markdown code block, indented with four spaces:

	body {
	 background: $body-color url(img/bg.jpg);
	 color: $text-color;
	 font-family: $serif-ff;
	 @include font-size(16px);
	}

Octopress also allows for Github-style "backtick" code blocks. Here a few examples:

```
$ cd /Users/john_doe/projects
```

And a fancy one with syntax highlighting and a title:

``` css Sass Variables
a:hover {
  color: $link-color-hover;
  border-bottom: 1px dotted $link-color-hover;
  text-decoration: none;
  }
```





[^1]: Footnotes! You'll have to use the 'kramdown' markdown processor to use them.

[1]: http://www.cnn.com
