require 'rake'

task default: :test

task test: :format do
  sh 'mix test'
end

task :format do
  sh 'mix format'
end

task :credo do
  sh 'mix credo --strict'
end
