require "bundler/gem_tasks"
require 'rubocop/rake_task'
task :default => :spec

RuboCop::RakeTask.new(:lint) do |task|
  task.patterns = ['lib/**/*.rb']
  task.fail_on_error = false
end