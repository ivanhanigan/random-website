## random-website

There are many templates for jekyll sites (a tool that helps build static HTML page websites from markdown).

However they are often quite complicated and the techniques for configuring them are esoteric. Reading the instructions is kind of hard work even though the jekyll team have put a lot of effort in to some great resources like this site: https://jekyllrb.com/docs/posts/.

So I started this project in an attempt to make it a bit simpler.  This is as simple as I could make it in the time I had available.

I hope that my children, colleagues and students can also use this.

You can edit the files directly in Github which is quite straightforward (the automatic Actions tool will build the site and display it at https://your-git-name/random-website), but to develop the website locally to test before making it live you need to be able to run: 

```
jekyll serve
```

Which is easy on linux. Perhaps if you are on windows it is possible after you install windows sub linux (WSL) 

```
wsl --install
```

and I tested this on an old windows box and installed WSL Ubuntu 22.04, then followed these instructions:

https://idroot.us/install-jekyll-ubuntu-22-04/
