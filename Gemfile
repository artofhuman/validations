source 'http://rubygems.org'
gemspec

unless ENV['TRAVIS']
  gem 'byebug', require: false, platforms: :mri
  gem 'yard',   require: false
end

gem 'hanami-utils', '1.1.0.rc1', require: false, git: 'https://github.com/hanami/utils.git', branch: 'develop'

gem 'hanami-devtools', require: false, git: 'https://github.com/hanami/devtools.git'
gem 'i18n', '~> 0.7',  require: false
gem 'coveralls',       require: false
