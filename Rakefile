require 'rake'
require 'rake/testtask'

task default: [:test]

desc 'Run unit tests'
Rake::TestTask.new('test') do |t|
  t.pattern = 'test/test_google_drive.rb'
  t.verbose = false
  t.warning = false
end
