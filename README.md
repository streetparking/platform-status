# platform-status
Static site that takes the latest post by catigory to display status of features. Additionally shows release notes and initial paragraph of each. Allowing for easily accessable and updatable place to communicate updates and statuses.

# Public viewable site
Branch `gh-pages` is what's being published. Any time a push to the branch is made github will rebuild.

# running locally First time
1. pull down the branch
2. `gem install`
3. `bundle install`
3. `bundle exec jekyll serve`
4. visit http://localhost:4000

## thereafter
1. `bundle exec jekyll serve`
2. visit http://localhost:4000

# creating new release note
1. make sure in gh-pages branch
2. find posts folder
3. copy release note template
4. update name of new copied file
5. update title and date appropriately
6. add body text
7. save file 
8. go to terminal ctrl c to stop server or open new tab
- `git status` check what changedd
 - `git add .` add changes
 - `git commit -m" helpful text to know what changed"` comment for self and team what changed 
 - `git push origin gh-pages` push up changes to branch and to be deployed by github.

# Stack
We're using Jekyll to compile markdown files into a static site behind the scenes using ruby. To do any  templating searching Jekyll helps though it is based on liquid. Jekyll specific docs are at https://jekyllrb.com/docs/ Markdown help 

Helpfull resources are [jekyll docs](https://jekyllrb.com/docs/) and [Markdown cheatsheet] (https://www.markdownguide.org/cheat-sheet/).