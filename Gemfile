source "https://rubygems.org"
ruby RUBY_VERSION

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "3.9.0"

# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima", "~> 2.5"

# install html-proofer
gem "html-proofer"

# install kramdown-parser-gfm (from kramdown version 2 this is needed)
gem "kramdown-parser-gfm"

# speed up parallel github fetches
gem "parallel"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins

gem "rest-client", "~> 2.1"

# If you have any plugins, put them here!
group :jekyll_plugins do
   gem 'jekyll-seo-tag'
   gem 'jekyll-redirect-from'
   gem 'jekyll-paginate-v2'
   gem 'jekyll-toc'
   gem 'jekyll-sitemap'
   gem 'jekyll-tagging'
   gem 'hawkins'
   gem 'liquid-nested-sort', '~> 0.1.5'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data'

gem 'searchyll', :git => 'https://github.com/italia/developers-italia-searchyll'

gem "octokit", "~> 4.18"