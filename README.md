Haynie Research & Development GitHub Page
=========================
[![Build Status](https://travis-ci.org/haynieresearch/haynieresearch.github.io.svg?branch=master)](https://travis-ci.org/haynieresearch/haynieresearch.github.io)

Just a simple GitHub page!

Development
-----------

### Run the site locally
```bash
gem install bundler # first time only
bundle install # first time only
bundle exec jekyll serve
```

### Update list of repos:
```bash
pip install pystache requests pygithub3 # first time only
./generate.py
```

### Visit local Site
http://localhost:4000
