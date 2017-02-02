source 'http://rubygems.org'

group :default do
  gem 'rack', '~> 1.5.4' # This change was made via Snyk to fix a vulnerability
  gem 'rake', "~> 10.0.4"
  gem 'grape', "~> 0.4.1"
  gem 'activerecord', '~> 3.2.22.1' # This change was made via Snyk to fix a vulnerability
  gem 'json', '~> 1.7.7'
  gem 'grape-swagger'
  gem 'rack-cors', :require => 'rack/cors'
  gem 'mysql2', "~> 0.3.11"
  gem "schema_plus", "~> 0.4.1"
end

group :test, :development do
  gem 'rspec'
  gem 'rack-test', require: "rack/test"
  gem 'shotgun', '~> 0.9' # This change was made via Snyk to fix a vulnerability
end