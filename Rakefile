#require 'rspec/core/rake_task'
#task :default => :spec
#RSpec::Core::RakeTask.new

task :default => ["my_task"]
desc "Print reminder about eating more fruit."

task :my_task => ["task_two"] do
  puts "Eat more apples!"
end

task :task_two => ["shell_task"] do
  puts "In task_two"
end

desc 'Run unit tests'
task :shell_task do
    sh 'ls -ltr'
end
