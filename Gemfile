# frozen_string_literal: true

source "https://rubygems.org"

gem 'cocoapods', '~> 1.9.0'
gem 'cocoapods-rome', git: 'https://github.com/djbe/Rome'
gem 'fastlane', '~> 2.134'

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
