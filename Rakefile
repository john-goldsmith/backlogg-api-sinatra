require 'rake'
require './boot'
require 'sinatra/activerecord'
require 'sinatra/activerecord/rake'

task default: [:console]

desc "Loads a Pry console"
task :console do
  require 'pry'
  system("bundle exec pry -r ./boot.rb")
end

task c: :console
task pry: :console