This blog runs on [Jekyll](http://jekyllrb.com/docs/home/)

Install dependencies with `bundle install`.

## Running 

	$ jekyll serve --watch
	
Run with drafts:

	$ jekyll serve --watch --drafts

## Publishing

```
 git commit -m "Do some changes"
 bundle exec jekyll build 
 git add .
 git commit -m "Regenerate"
 git push origin source
 rake publish 
 git push origin master
```
