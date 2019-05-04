* Nothing much to see here.  This is just a *sample* **repository** so I can get a feel for how _*GitHub*_ works.

* This is the updated README file for repo0.
* With a <strike>second</strike> third line.

Do relative links work
- Like this? [foo.html](foo.html) -- Yes, the link is to the web page for the file.
- Like this? [foo.html](repo0/foo.html) -- No.
- Like this? [foo.html](Keith-S_Thompson/repo0/foo.html) -- Yes, the link is to the web page for the file.

Do relative links work?  [foo.html]  Yes!  Again, the link is to the web page for the file.

TODO Figure out how to get a relative link to display the file itself
for plain text, or interpreted as html for `*.html` files.  But this will do for now.
(My main motivation for this is the `README.md` files for my `fizzbuzz-c` and `fizzbuzz-polyglot` repos.)

Plain-text [README].

I think I've got relative links worked out.  For example, for the
above `README` link, I wrote `[README]`, then `[README]: README` as a
link reference definition (at the bottom of this file).  Likewise for
`foo.html`.  Making the link text be something other than the name of
the file should also be possible, but so far I don't have a requirement
for that.

Trying several kinds of links:

- This file: [https://github.com/Keith-S-Thompson/repo0/blob/master/README.md](https://github.com/Keith-S-Thompson/repo0/blob/master/README.md) (works, but really ugly)
- Full URL: [https://github.com/Keith-S-Thompson/repo0/blob/master/foo.html](https://github.com/Keith-S-Thompson/repo0/blob/master/foo.html) (works, but really ugly)
- Simple relative file name: [foo.html](foo.html) (doesn't work)
- Longer relative path: [repo0/blob/master/foo.html](repo0/blob/master/foo.html) (works, but a bit ugly)

Haven't touched this in a while.  Here's a new line.

[README]: README
[foo.html]: foo.html
