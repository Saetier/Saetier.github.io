# frozen_string_literal: true

source "https://rubygems.org"
gem 'tzinfo'
gem 'tzinfo-data' # 윈도우 환경에서는 이 gem도 필요합니다.
gem 'wdm', '>= 0.1.0', if: Gem.win_platform?

gemspec

group :test do
  gem "html-proofer", "~> 5.0"
end
