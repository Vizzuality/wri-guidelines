# WRI guidelines
This repository is the WRI guidelines project

## Getting set up

The dashboard is powered by
[Jekyll](https://upload.wikimedia.org/wikipedia/commons/7/78/Dr_Jekyll_and_Mr_Hyde_poster_edit2.jpg).
Once you've installed the Jekyll gem and other deps, you can use npm to
build and run the application:

```
gem install bundler
bundle install

jekyll serve
```

[Go go go!](http://localhost:4000/wri-guidelines)

## Jekyll

### Adding new pages

In development, and on Github Pages, requests are rewritten to `.html`
files as necessary. For example, `/countries --> /countries.html`. So,
creating a new page is easy: just add a new HTML file! Jekyll will
handle compilation, and the middleware will handle rewriting.


Github Pages handles all the building, etc. for you. [Check it
out!](http://vizzuality.github.io/wri-guidelines)


