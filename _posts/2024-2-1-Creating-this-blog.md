---
layout: post
title: Creating this blog
---

*Document* is one of the principles I mentioned wanting to uphold at the [Start of a journey](https://zweanslord.github.io/spacetraders-blog/Start-of-a-journey/). Given I have made this blog, the first step therefore will be to document how I made this blog.

## The parts at work

For this blog, the following parts are essential:

- [GitHub](https://github.com/)! The code running the blog, as well as the blog contents, are kept under version control with [Git](https://git-scm.com), and stored on github. The code respository containing this blog can be found at: [https://github.com/zweanslord/spacetraders-blog]

- [GitHub Pages](https://pages.github.com/) is the site host. It is visible in the page URL in the browser, as this blog is hosted at [https://zweanslord.github.io/spacetraders-blog/]. When going to [https://zweanslord.github.io] no result will appear, but github pages can host a page for the github user there, and that which follows the url, in this case "spacetraders-blog", indicates the project for which GitHub Pages is hosting a page.

- [Jekyll](https://jekyllrb.com/) which is a the tool that changes text files into a fancy looking blog.

- [Jekyll Now](https://www.jekyllnow.com/) is effectively a code repository at GitHub which makes setting up a Jekyll blog a very quick process.

## How to create a blog

Now, if you as reader want a blog like this, the required steps can basically be summed up to four steps: 
1. Create a [GitHub](https://github.com/) account, if you don't already have one
2. Fork the [jekyll-now repository](https://github.com/barryclark/jekyll-now) to your own github account
3. Follow the instructions at Jekyll Now to customize your site in the _config.yml, changing the name, description and avatar
4. Start blogging by making new post files in the directory "_posts" in the format of "2024-2-1-Creating-this-blog.md", which is "<Year>-<Month>-<Day>-<Title>.md", which can be done through the GitHub site.

And tadaa, you now have a blog!

## The cost in time

Now, I spent way too much time on actually doing the above steps. Because those are not the only ways ot set this up. There is a [GitHub setup guide](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll) which tells about setting up Jekyll. There are ofcourse [Jekyll Docs](https://jekyllrb.com/docs/) and I was also looking at the option of using [another theme](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll) or how to make a list of all posts made, as mentioned at Jekyll documentation about [posts](https://jekyllrb.com/docs/posts/#displaying-an-index-of-posts). One nice looking theme is [Midnight](https://pages-themes.github.io/midnight/), though it unfortunately lacks an About page, and offers downloads buttons which I am not interested in. Its dark theme does look more fitting for a blog about space traders than a white one, though. Another interesting thing would be to add buttons for previous or next posts, such as explained on [another blog](https://guypursey.com/blog/202104171135-next-previous-nav-links-jekyll-blog) I found thanks to google.

Ultimately, I spent way too much time on reading, as opposed to actually doing things. One of the principles I want to follow is *Share*, by making quick steps forward and iterate on them. Yet those steps are meant for work on [SpaceTraders API](https://spacetraders.io/), not on this blog. Setting up ruby for Jekyll, checking out the code of this blog, none of those actually help me with space traders, though it has been a fun distraction. For now, however, this blog post about it will have to do, so next time I find time, I will actually work on space traders instead of setting up the blog.
