require 'rake'
require 'rake/testtask'

task :default => :test

Rake::TestTask.new do |t|
  t.pattern = "test/**/*_test.rb"
  t.libs += ['test']
end