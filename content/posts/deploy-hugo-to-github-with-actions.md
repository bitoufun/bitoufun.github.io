---
title: "deploy hugo to github with actions"
date: 2020-09-15T11:30:03+00:00
# weight: 1
# aliases: ["/first"]
tags: ["first"]
author: "Me"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "Desc Text."
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/bitoufun/content"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---



# deploy hugo to github with actions

- Create a repo
- Deploy with actions
- Use [actions-hugo](https://github.com/peaceiris/actions-hugo)
	- Create `.github/workflows/gh-pages.yml`
	- Do this [Create SSH Deploy Key](https://github.com/peaceiris/actions-gh-pages#%EF%B8%8F-first-deployment-with-github_token)
- Git clone
- Install [theme](https://github.com/adityatelange/hugo-PaperMod)
- `git add . && git commit -m "update" && git push`
- Actions: build -> deploy

> Almost do nothings to deploy the hugo blog?
> Thanks to peaceiris.
