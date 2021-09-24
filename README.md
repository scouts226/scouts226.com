# Scouts 226 Website

To test locally, you need to have a recent-ish version of ruby installed (ruby
2.4 or newer). Run the following to get up and running:

```
gem install bundler
bundle install
bundle exec jekyll serve -l
```

That should install jekyll and its dependencies, then start a live server.

## Layouts

If you write a simlpe page, often in markdown for the website, you will probably
use the `default` layout. It has a single row and a 12 column div ready for your
content. If your page has multiple rows, the `main` layout is what you want. In
this layout, you are responsible for creating your own divs for the rows and
columns.

## References

* [Jekyll Quickstart](https://jekyllrb.com/docs/)
* [BSA Style Guide](https://41zfam1pstr03my3b22ztkze-wpengine.netdna-ssl.com/wp-content/uploads/2019/08/310-132019-BSA-Brand_WEB_sm.pdf)
