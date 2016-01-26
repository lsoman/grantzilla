source "https://rubygems.org"

gem "rails", "~> 4.2"
gem "pg"
gem "sass-rails", "~> 5.0"
gem "uglifier", ">= 1.3.0"
gem "coffee-rails", "~> 4.1.0"
gem "devise"

gem "jquery-rails"
gem "turbolinks"
gem "jbuilder", "~> 2.0"
# bundle exec rake doc:rails generates the API under doc/api.
gem "sdoc", "~> 0.4.0", group: :doc
gem "newrelic_rpm"

# paperclip with support for S3 storage with aws-sdk v2
# has not been published yet but is on master as of 1/22/16.
gem "paperclip", github: "thoughtbot/paperclip"
gem "rmagick"

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem "byebug"
  gem "rspec-rails", "~> 3.4"
  gem "rubocop", "~> 0.36"
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem "web-console", "~> 2.0"

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem "spring"
  gem "letter_opener"
end

group :production do
  gem "aws-sdk"
  gem "mailgun_rails"
end
