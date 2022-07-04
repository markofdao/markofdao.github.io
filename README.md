## Overview

Blog of Dmytro Baimuratov

## Installation

Install required gems using `bundle`:
```bash
bundle install
```

Install Webrick:
```bash
bundle add webrick
```

Run the blog in localhost:
```bash
bundle exec jekyll serve
```

## Deploy to Github Pages

To publish your site to [Github Pages](https://pages.github.com/), change `theme: xxx` in `_config.yml` to `remote_theme: huangyz0918/moving` then push to your github repo (this is important, or you will get an error from github pages that not support the moving theme). 

To test your site locally, change that to `theme: moving` and build again.

## Internal links

- [Link to a document]({{ site.baseurl }}{% link _collection/name-of-document.md %})
- [Link to a post]({{ site.baseurl }}{% link _posts/2021-07-26-name-of-post.md %})
- [Link to a page]({{ site.baseurl }}{% link news/index.html %})
- [Link to a file]({{ site.baseurl }}{% link /assets/files/doc.pdf %})

## Credits

The [original theme](https://github.com/huangyz0918/moving) was created by @huangyz0918.