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
