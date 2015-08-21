source 'https://rubygems.org'

gem 'solrizer'
gem 'puma'
gem 'sufia', '6.3.0'
gem 'kaminari', github: 'jcoyne/kaminari', branch: 'sufia'  # required to handle pagination properly in dashboard. See https://github.com/amatsuda/kaminari/pull/322
gem 'hydra-role-management'
gem 'cancan'
# Primary Hydra Dependency
# # gem 'hydra', '~> 9.0.0'
 gem 'blacklight_advanced_search'
# # # # UMichwrapper
gem 'umichwrapper', github: 'mlibrary/umichwrapper', branch: 'master'
#   #  #
#   #  # # Preemptively require gems so that rails generate hydra:install will complete.
#   #  # #   This is a vendorized gems issue with Bundle.with_clean_env
      gem 'orm_adapter'
          gem 'responders'
               gem 'warden'


                                   gem 'bcrypt'
                                    gem 'thread_safe'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.1'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
 gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end


gem 'rsolr', '~> 1.0.6'
gem 'devise'
gem 'devise-guests', '~> 0.3'
group :development, :test do
  gem 'rspec-rails'
  gem 'jettywrapper'
end
