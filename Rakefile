require 'rspec/core/rake_task'

RSpec::Core::RakeTask.new(:spec) do |task|
  task.rspec_opts = %w(--color --format d)
end

task default: :spec

task :console do
    exec "irb -r retriever  -I ./lib"
end
