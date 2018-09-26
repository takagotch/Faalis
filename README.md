### Faalis
---

http://faalis.io/
https://rubygems.org/gems/faalis/versions/2.2.1
https://github.com/Yellowen/Faalis/

Gemfile
```
source 'http://rails-assets.org' do
  gem 'rails-assets-sugar'
  gem 'rails-assets-bootstrap-rtl'
  gem 'rails-assets-jqueyr-knob'
  gem 'rails-assets-bootstrap-daterangepicker'
  gem 'rails-assets-jquery-sparkline'
  gem 'rails-assets-jquery-icheck'
  gem 'rails-assets-admin-lte'
end

gem "faalis"
```
```sh
bundle install
rails g faalis:install

rake db:migrate db:seed
```
```
config/environments/development.rb
config.action_mailer.default_url_optons = { :host => 'localhost:3000' }
```
