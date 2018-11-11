# carpentry-theme

Welcome to the carpentry Jekyll theme! In this directory, you'll find the files you that any carpentries lesson needs to use.

## Usage

Add this line to your Jekyll site's `_config.yml`:

```yaml
theme: swcarpentry-i18n/carp-theme
```

### gh-pages

You shouldn't need to add anything else. GH should build the page.

### locally

Create a Gemfile in your root directory with this content:
```ruby
source 'https://rubygems.org'
gem 'github-pages', group: :jekyll_plugins
```

and to install the dependencies, run

```bash
bundle
```

Once all it's there, you can preview your site doing:

```bash
bundle exec jekyll serve
```


## Contributing

Bug reports and pull requests are welcome! This project is intended to be a
safe, welcoming space for collaboration, and contributors are expected to adhere
to the [Carpentries' Code of
Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html).

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When the theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `carpentry-theme.gemspec` accordingly.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

