require "bundler/gem_tasks"
require "rspec/core/rake_task"
require 'ci/reporter/rake/rspec' 

RSpec::Core::RakeTask.new(:spec => ["ci:setup:rspec"])

task :default => :spec
task :test => :spec



