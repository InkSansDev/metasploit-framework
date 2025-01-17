source 'https://rubygems.org'

gemspec name: 'metasploit-framework'

# separate from test as simplecov is not run on travis->
group :coverage do
  gem 'simplecov', '0.18.2'
end

group :development do
  gem 'redcarpet'
  gem 'yard'
  gem 'pry-byebug'
  gem 'debug', '>= 1.0.0'
  gem 'octokit'
  gem 'memory_profiler'
  gem 'ruby-prof', '1.4.2'
  # Uncomment this line if using metasploit-aggregator
  # gem 'metasploit-aggregator'
end

group :development, :test do
  gem 'rake'
  gem 'rspec-rails'
  gem 'rspec-rerun'
  gem 'rubocop'
end

group :test do
  gem 'test-prof'
end

# Override nokogiri to a specific version
gem 'nokogiri', '~> 1.18.1'  # Change this line if needed
