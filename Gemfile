source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

source 'https://rubygems.org'
ruby '2.4.0'
gem 'rails', '4.0.1'
# Rails defaults
gem 'sqlite3'
gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'
# learn-rails
gem 'activerecord-tableless'
gem 'compass-rails', '~> 2.0.alpha.0'
gem 'figaro'
gem 'gibbon'
gem 'google_drive'
gem 'high_voltage'
gem 'simple_form'
gem 'zurb-foundation'
group :development do
gem 'better_errors'
gem 'quiet_assets'
gem 'rails_layout'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
