source 'https://rubygems.org'

# Specify your gem's dependencies in reform-rails.gemspec
gemspec

# gem "reform", github: "trailblazer/reform"
# gem "reform", path: "../reform"

rails_version = ENV['RAILS_VERSION'] || '4.2'

# bored of wrestling with rails...
if rails_version == '4.0'
  gem 'mongoid', '~> 4'
end

gem "railties", "~> #{rails_version}"
gem "activerecord", "~> #{rails_version}"
