ruby '2.5.1'
source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = format('%s/%s', repo_name, repo_name) unless repo_name.include?('/')
  format 'https://github.com/%s.git', repo_name
end

gem 'jekyll'
gem 'jekyll-seo-tag'

group :development, :test do
  gem 'mry', require: false
  gem 'rubocop', '~> 0.58.2', require: false
end
