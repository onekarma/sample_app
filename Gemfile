source 'https://rubygems.org'

gem 'rails', '3.2.1'

group :production, :staging do
  gem "pg"
end

group :development do
	gem 'rspec-rails', '2.0.0.beta.18'
	gem "sqlite3-ruby", "~> 1.3.0", :require => "sqlite3"
end

group :test do
	gem 'rspec', '2.0.0.beta.18'
    gem "sqlite3-ruby", "~> 1.3.0", :require => "sqlite3"
end
