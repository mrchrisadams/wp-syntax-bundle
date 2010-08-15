# This is barely a project, but it's (probably) worth sharing anyway 

I've been pasting a fair few code snippets in my own Wordpress blog lately, that uses wp-syntax to provide nice readable code samples. All this bundle does is fill in the typical pasting syntax for me automatically, so I don't need to keep looking it up.

It's been useful to me, so I figured someone else might find it useful too, and besides I wanted to learn how to make bundles for Textmate.

### How to use it

All you need to to here to get the usual snippet like this:

 <pre lang="bash" line='1'>
    //code goes here
 </pre>

Is do something like this:
 
1 - Make sure you're using Markdown for your syntax highlighting / scope
2 - type `code`
3 - hit tab to spit out the boilerplate
4 - type the language for highlighting
5 - hit tab to decide if you want line numbering or not
6 - hit tab one more to jump the cursor inside, the `pre` block start adding code