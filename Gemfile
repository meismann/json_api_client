source "https://rubygems.org"

gemspec

gem 'rake'

as_version = ENV["AS_VERSION"] || "default"

as_version = case as_version
when "default"
  ">= 3.2.0"
else
  "~> #{as_version}"
end

gem "activesupport", as_version

gem "codeclimate-test-reporter", group: :test, require: nil
