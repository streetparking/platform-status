# platform-status
Static site that takes the latest post by catigory to display status of features. Additionally shows release notes and initial paragraph of each. Allowing for easily accessable and updatable place to communicate updates and statuses.

# Public viewable site
Branch `gh-pages` is what's being published. Any time a push to the branch is made github will rebuild.

# running locally
1. pull down the branch
2. `gem install`
3. `jekyll serve` or `bundle exec jekyll serve`
4. visit http://localhost:4000/platform-status/

# Stack
We're using Jekyll to compile markdown files into a static site behind the scenes using ruby. To do any  templating searching Jekyll helps though it is based on liquid. Jekyll specific docs are at https://jekyllrb.com/docs/ Markdown help 

Helpfull resources are [jekyll docs](https://jekyllrb.com/docs/) and [Markdown cheatsheet] (https://www.markdownguide.org/cheat-sheet/).