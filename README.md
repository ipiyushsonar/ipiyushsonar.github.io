<p align="center">
    <h2 align="center">
        My Developer Portfolio & Website
        <p style="padding-top:3px"> <a href="https://app.netlify.com/sites/ipiyushsonar/deploys"><img src="https://api.netlify.com/api/v1/badges/00127c51-3cff-469b-8ee3-1800806fc20f/deploy-status" alt="Build Status" data-canonical-src="https://app.netlify.com/sites/ipiyushsonar/deploys"></a></p>
        <p style="padding-top:3px"> <a href="https://travis-ci.org/ipiyushsonar/ipiyushsonar.github.io.svg?branch=master"><img src="https://travis-ci.org/ipiyushsonar/ipiyushsonar.github.io.svg?branch=master" alt="Build Status" data-canonical-src="https://travis-ci.org/ipiyushsonar/ipiyushsonar.github.io.svg?branch=master"></a></p>
    </h2>
</p>

<p align="center">This is a simple and minimalist portfolio site built using Jekyll for those who like simplicity.</p>

***

<p align="center">
    <b><a href="README.md#what-has-inside">What has inside</a></b>
    |
    <b><a href="README.md#setup">Setup</a></b>
    |
    <b><a href="README.md#settings">Settings</a></b>
    |
    <b><a href="README.md#how-to">How to</a></b>
</p>

<p align="center">
    <img src="https://raw.githubusercontent.com/sergiokopplin/indigo/gh-pages/assets/screen-shot.png" />
</p>

## What has inside

- [Jekyll](https://jekyllrb.com/), [Sass](https://sass-lang.com/) ~[RSCSS](https://rscss.io/)~ and [SVG](https://www.w3.org/Graphics/SVG/);
- Tests with [Travis](https://travis-ci.org/);
- Google Speed: [98/100](https://developers.google.com/speed/pagespeed/insights/?url=http%3A%2F%2Fsergiokopplin.github.io%2Findigo%2F);
- No JS. :sunglasses:

## Setup

1. Fork the project [Indigo](https://github.com/sergiokopplin/indigo/fork)
2. Edit `_config.yml` with your data (check <a href="README.md#settings">settings</a> section)
3. Write some posts :bowtie:

If you want to test locally on your machine, do the following steps also:

1. Install [Jekyll](https://jekyllrb.com), [NodeJS](https://nodejs.org/) and [Bundler](https://bundler.io/).
2. Clone the forked repo on your machine
3. Enter the cloned folder via terminal and run `bundle install`
4. Then run `bundle exec jekyll serve --config _config.yml,_config-dev.yml`
5. Open it in your browser: `http://localhost:4000`
6. Do you want to use the [jekyll-admin](https://jekyll.github.io/jekyll-admin/) plugin to edit your posts? Go to the admin panel: `http://localhost:4000/admin`. The admin panel will not work on GitHub Pages, [only locally](https://github.com/jekyll/jekyll-admin/issues/341#issuecomment-292739469).

## Settings

You must fill some informations on `_config.yml` to customize your site.

```
name: John Doe
bio: 'A Man who develops software with coffee'
picture: 'assets/images/profile.jpg'
...

and lot of other options, like width, projects, pages, read-time, tags, related posts, animations, multiple-authors, etc.
```

## How To?

Check the [FAQ](./FAQ.md) if you have any doubt or problem.

---
## License

[MIT](http://piyush.mit-license.org/) License © Piyush Sonar
