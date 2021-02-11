---
layout: single
title:  "Why I built my blog with GitHub Pages and what I learned from it"
date:   2020-11-20 12:22:30 +0100
categories: general
header:
  image: /assets/images/code_typing.png
  teaser: /assets/images/programming_teaser.png

---

I wanted to create a blog for quite some time and of course the first question was, what platform to use? Should I just register on a site like [Blogger.com](https://www.blogger.com/about/?bpli=1)? Should I use a site builder like [Wix](https://www.wix.com/)? Or, should I also learn a thing or two along the way? You probably guessed it, I went with the last one :)
{: .text-justify}

---

So, [GitHub Pages](https://pages.github.com/) is a service that GitHub offers its users, where you can build your own website. The principle is simple, you create a Git repository on GitHub, following a certain naming convention (your username, followed by the github.io suffix, hence my blog is *rbogi.github.io*). Then, you can use [Jekyll](https://jekyllrb.com/) to create a static website. 
{: .text-justify}

Jekyll is a framework written in Ruby. I do not know any Ruby or web development myself, nor do I intend to learn it at the moment. However, you do not need to possess any of these skills, as you can write your posts in Markdown (edit: check out my post about Markdown), and just use some simple command line commands to compile your site preview locally, and of course push your changes to GitHub, where they will automatically render as a nice website in your browser. You simply need to study the Jekyll documentation carefully, follow the instructions there and it is really a straightforward process. Installation, especially on Linux is very easy and fast, [using Teriminal](https://jekyllrb.com/docs/installation/ubuntu/).
{: .text-justify}

One very nice thing is that you can choose a theme for your website. The ones that come out of the box and are [supported by GitHub Pages](https://pages.github.com/themes/) are pretty dull. But, there is a community out there who write compatible [Jekyll themes](https://jekyllthemes.io/github-pages-themes) and there are some awesome ones! I chose one that is called [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) (pun intended, I guess), developed by Michael Rose to whom kudos and a big shout out are due!. I think it looks pretty neat!
{: .text-justify}

I recommend choosing a well documented theme, as initially you will need all the help you can get. Especially when you get into customizing your content with [YAML Front Matter](https://jekyllrb.com/docs/front-matter/), which is basically a special syntax, kind of meta-information that you can enter at the beginning of your file (like your Markdown document for your blog post) and it will be interpreted by the framework.
{: .text-justify}

Why would you go through all of that for the sake of a blog that doesn't even look as professional as a Wix page and is static? Well, because you can learn and practice many things along the way. First of all, you will read and learn from technical documentation, use Git, a command line utility, you will install and configure new software, and so on. I think when your website successfully renders for the first time properly, it will be surely worth it.
{: .text-justify}

This is my first blog post and I hope you enjoyed it. There is more to come, I plan to concentrate on technical skills, sharing my journey as I discover new stuff.
{: .text-justify}

