source 'https://rubygems.org'

gemspec

group :tools do
  gem 'pry'
end

group :test do
  gem 'byebug', platform: :mri
  gem 'rack', '>= 1.0.0', '<= 2.0.0'
  gem 'slim'

  gem 'simplecov'
  gem 'codeclimate-test-reporter'
end

group :benchmarks do
  gem 'benchmark-ips'
  gem 'actionview'
end
