# henryfbp.github.io
Henry Post's professional website

<https://henryfbp.github.io>

## Requirements

-   Ruby 2.6.5 (works for me on Windows)
    -   Bundler (`gem install bundler`)

### Notes

- You may need MSYS2 (`ridk install`) if using Windows.
- `choco install ruby` MIGHT give you the WRONG ruby version.
	- If this happens, uninstall ruby, and run `choco install ruby --version=2.6.5`.


## Testing locally

Run `bundle install` in this directory to install Jekyll and other deps.

To run the server locally, run `bundle exec jekyll serve --watch` in this directory. See `scripts/` for more scripts.

## Jekyll Stuff

### Similar Jekyll sites

For inspiration or Jekyll/Liquid/Front Matter tips.

<https://github.com/jokecamp/jokecamp.com>

### Jekyll tips

<https://stackoverflow.com/questions/25452429/excluding-page-from-jekyll-navigation-bar>
<https://stackoverflow.com/questions/38891463/jekyll-default-installation-doesnt-have-layouts-directory>
<https://github.com/jekyll/minima>
<https://jekyllrb.com/tutorials/navigation/#scenario-9-nested-tree-navigation-with-recursion>
