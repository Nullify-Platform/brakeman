source "https://rubygems.org"

gemspec :name => "brakeman"

unless ENV['BM_PACKAGE']
  gem "rake", "< 13.2.2"
  gem "codeclimate-test-reporter", group: :test, require: nil
  gem "json", "< 2.10.1", group: :test, require: nil # For Ruby 1.9.3 https://github.com/colszowka/simplecov/issues/511
end
