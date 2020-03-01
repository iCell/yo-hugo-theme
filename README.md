# Yo

Yo is a responsive blog theme for [hugo](https://github.com/gohugoio/hugo), which is specialized in presenting writing layout like long essay or technical writing.

## Installation

Change into Hugo directory then:

```
cd themes
git clone https://github.com/iCell/yo-hugo-theme.git
```

More detailed instruction at [Hugo Docs](http://gohugo.io/themes/installing-and-using-themes/).

Using `git submodule` is recommended instead of git clone.

```
cd themes
git submodule add https://github.com/iCell/yo-hugo-theme.git yo
```

## Configuration

You can check inside the `exampleSite` folder for content example and `config.toml`.

Yo use `bulma` and `node-sass` as css develop dependencies, the following command maybe helpful if you need to make some changes to the theme.

```
npm build-css
npm watch-css
```

## Support and Pull Requests

Please use GitHub issues to file bugs. If you can help fixing bugs, optimize the theme or adding features, please do pull requests, I really love to see what others can come up with.
