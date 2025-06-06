## Build site

To build the website locally, clone the repo with:

```
git clone https://github.com/fhe4cv/fhe4cv-website.git
```

Then install necessary Ruby dependencies by running `bundle install` from within the `website` directory.  After this, the site can be be built with:

```
bundle exec jekyll build
```

To view the site, run `bundle exec jekyll serve` and point a browser to `http://localhost:4000/`.  More information on Jekyll can be found [here](http://jekyllrb.com/).
