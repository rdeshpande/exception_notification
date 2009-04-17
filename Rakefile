require 'rake'
require 'rake/testtask'

task :default => [:test]

task :test do
  Dir.glob('test/**/*_test.rb').each do |f|
    system("ruby -Itest #{f}")
  end
end

