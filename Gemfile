source 'https://rubygems.org'

# Basic rails and standard associated libraries
gem 'rails', '3.2.2'
gem 'thin'
gem 'foreman'
gem 'jquery-rails'
gem 'sass-rails', '>= 3.2.3'
gem 'bootstrap-sass', '>= 2.0.1'
gem 'haml', '>= 3.1.4'
gem 'heroku'

# Authentication and authorization
gem 'devise', '>= 2.0.0'
gem 'omniauth'
gem 'cancan'

# Social integrations
gem 'twitter'
gem 'linkedin'
gem 'fb_graph'
gem 'octopi'
gem 'google-api-client'

# View DRY Helpers
gem 'simple_form'
gem 'show_for'
gem 'kaminari'

# Controller DRY Helpers
gem 'inherited_resources'
gem 'meta_search', '>= 1.1.0'

# API framework DSL
gem 'grape', git: 'https://github.com/intridea/grape.git', branch: 'frontier'

# Background job/queue
gem 'redis'
gem 'resque'

# Feature/beta enablement
gem 'rollout'
gem 'degrade'

# ACH file generation
gem 'ach', git: 'https://github.com/goodwink/ach.git'

# Stripe credit card payments
gem 'stripe'

# Dwolla payment service
gem 'dwolla'

# Twilio voice and sms gateway
gem 'twilio-ruby'

# Airbrake/Errbit exception logging
gem 'airbrake'

# Hominid MailChimp interface
gem 'hominid'

# Postmark ActiveMailer binding
gem 'postmark-rails'

# Olark live support chat
gem 'rack-olark'

# Testing and development
group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails', '>= 2.8.1'
  gem 'guard'
  gem 'growl'
  gem 'libnotify' if RUBY_PLATFORM.downcase.include?("linux")
  gem 'guard-spork'
  gem 'guard-rspec'
  gem 'guard-rails'
  gem 'guard-sass'
  gem 'guard-bundler'
  gem 'spork', '>= 1.0.0.rc2'
  gem 'rb-inotify' if RUBY_PLATFORM.downcase.include?("linux")
  gem 'rb-fsevent' if RUBY_PLATFORM.downcase.include?("darwin")
end

# Heroku production
group :production do
  gem 'pg'
end

# Asset built-time only
group :assets do
  gem 'coffee-rails', '~> 3.2.1'
  gem 'therubyracer'
  gem 'uglifier', '>= 1.0.3'
end
