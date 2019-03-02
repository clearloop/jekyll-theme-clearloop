---
layout: default
title: Welcome to Clearloooooop!
slug: jekyll-theme-clearloop
---

# jekyll-theme-clearloop

Welcome to your new Jekyll theme! In this directory, you'll find the files you need to be able to package up your theme into a gem. Put your layouts in `_layouts`, your includes in `_includes`, your sass files in `_sass` and any other assets in `assets`.

To experiment with this code, add some sample content and run `bundle exec jekyll serve` – this directory is setup just like a Jekyll site!

TODO: Delete this and the text above, and describe your gem


## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-theme-clearloop"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: jekyll-theme-clearloop
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jekyll-theme-clearloop

## Usage

__Gemfile__:
```ruby
source "https://rubygems.org"

#Happy Clearlooping!
gem "jekyll", "~> 3.8"

#Plugins
group :jekyll_plugins do
  gem "jekyll-seo-tag"
  gem "rouge", "~> 3.3.0"
end
```

__\_config.yml__:
```ruby
# Welcome to Jekyll!

# Site settings
title: Your Website
email: Your Email
description: >-
  Description here

# Build settings
markdown: kramdown
highlighter: rouge
nsass:
  sass_dir: _sass
plugins:
  - jekyll-seo-tag

# posts
format: "%b %-d, %Y"
collections_dir: 
  collections

pcollections:
  categories:
    output: true
```

Basic Category page at `collections/_categories` ;)

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/hello. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `jekyll-theme-clearloop.gemspec` accordingly.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
