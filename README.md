# My Homepage - since 2019

What I done:

- I forked the repository of [dashingcode/front-cover](https://github.com/dashingcode/front-cover)
- I follow this macro [gist](https://gist.github.com/bilardi/6b6cdcfabed5e5976ba697544be714d6) guide
- I copied the main links of my [old site](https://github.com/bilardi/my.homepage.until.2019)
- I used my images into [cdn.bilardi.net/alessandra](https://github.com/bilardi/cdn.aws) and the free icons of [fontawesome.com](https://fontawesome.com/icons)
- move DNS on GitHub

## Development

```sh
docker-compose up # or postman-compose up
```

If something is not updated,

```sh
rm -rf _site .jekyll-cache .jekyll-metadata
touch .jekyll-metadata; chmod 777 .jekyll-metadata
touch Gemfile.lock; chmod 777 Gemfile.lock
```

Not commit (there are also in the .gitignore file)

* _site
* .jekyll-cache
* .jekyll-metadata
* Gemfile.lock

