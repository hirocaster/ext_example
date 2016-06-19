require "bundler/gem_tasks"
require "rspec/core/rake_task"
require "rake/extensiontask"

Rake::ExtensionTask.new("ext_example") do |ext|
  ext.lib_dir = "lib/ext_example"
end

RSpec::Core::RakeTask.new(:spec)

task :default => :spec
