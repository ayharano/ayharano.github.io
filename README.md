This project is based on [@ellekasai](https://github.com/ellekasai)'s [ResumeCards](https://github.com/ellekasai/resumecards), which is no longer maintained.

[![CircleCI](https://circleci.com/gh/ayharano/ayharano.github.io/tree/master.svg?style=shield&circle-token=:circle-token)](https://circleci.com/gh/ayharano/ayharano.github.io/tree/master)

ResumeCards is a Markdown based resume generator. It looks great on mobile/desktop and can be saved as PDF.

## :briefcase: Installation :briefcase:

**Note:** ResumeCards uses Jekyll. Please read [Jekyll's documentation](http://jekyllrb.com/) if you get stuck.

[Fork this repo](http://github.com/ayharano/ayharano.github.io/fork), clone it, and then run:

```
bundle install
```

...which installs `github-pages` gem. After that, run the server:

```
jekyll serve --watch
```
### Warning

* Once the server is started, you must go to [http://localhost:4000/](http://localhost:4000/), since `baseurl` is set as `""` initially. To use  http://localhost:4000/somewhere, change `baseurl` in `_config.yml` to `"/somewhere"` .

## Other instructions

Original repository and its instructions are located in [ellenkasai/resumecards](http://github.com/ellekasai/resumecards).

However, if it is no longer available, I forked and altered a bit to use CircleCI v2 and Firebase Hosting instead of GitHub Pages and such fork can be found at [ayharano/resumecards](http://github.com/ayharano/resumecards).
