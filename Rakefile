begin
  require 'rspec/core/rake_task'

  RSpec::Core::RakeTask.new(:spec)
  task :default => :spec

  task :gem do
    exec('gem build mundipagg_sdk.gemspec')
  end

rescue LoadError
    puts 'no rspec available'
end