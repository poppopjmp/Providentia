# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# core
gem 'bootsnap', '>= 1.4.2', require: false
gem 'haml-rails', '~> 2.0'
gem 'rgl'
gem 'pg'
gem 'puma'
gem 'nilify_blanks', '~> 1.4'
gem 'rails', '~> 7.1.3', '>= 7.1.3.3'
gem 'oj', '~> 3.10'
gem 'pry-rails', '~> 0.3.9'
gem 'rails-patterns'
gem 'friendly_id', '~> 5.5.0'
gem 'view_component'
gem 'jwt'
gem 'http', '~> 5.0'
gem 'turbo-rails', '~> 2.0', '>= 2.0.6'
gem 'liquid', '~> 5.5'
gem 'redis'
gem 'hiredis', '~> 0.6.3'
gem 'mail', '~> 2.8'
gem 'nokogiri', '~> 1.16'
gem 'stringex', '~> 2.8', require: 'stringex_lite'

# functionality
gem 'acts-as-taggable-on', '~> 10.0'
gem 'ipaddress', github: 'ipaddress-gem/ipaddress'
gem 'simple_form', '~> 5.3', '>= 5.3.1'
gem 'ancestry'
gem 'paper_trail', '>= 15.2.0'
gem 'kaminari'
gem 'naturally', '~> 2.2'

# markdown
gem 'redcarpet'
gem 'rouge'

# auth
gem 'devise'
gem 'omniauth', '~> 2.1', '>= 2.1.3'
gem 'omniauth_openid_connect', '>= 0.8.0'
gem 'omniauth-rails_csrf_protection', '>= 1.0.2'
gem 'pundit'

# frontend
gem 'propshaft', '>= 0.9.0'
gem 'vite_rails', '~> 3.0', '>= 3.0.18'

# monitoring
gem 'sentry-ruby'
gem 'sentry-rails', '>= 5.17.2'

group :development, :test do
  gem 'bundler-audit', '~> 0.9.1'
  gem 'brakeman'
  gem 'rubocop-rails_config', '>= 1.17.0'
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'rspec-rails', '>= 6.1.3'
  gem 'factory_bot_rails', '>= 6.4.4'
  gem 'rails-pg-extras', '>= 5.4.0'
  gem 'database_cleaner-active_record'
  gem 'faker', '~> 3.3'
end

group :development do
  gem 'listen'
  gem 'web-console', '>= 3.3.0'
  gem 'bullet'
  gem 'rack-mini-profiler', '>= 4.0.0'
  # For memory profiling
  gem 'memory_profiler'

  # For call-stack profiling flamegraphs
  gem 'flamegraph'
  gem 'stackprof'
end
