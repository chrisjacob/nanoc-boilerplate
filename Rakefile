require 'nanoc3/tasks'

# http://timeless.judofyr.net/grancher
require 'grancher/task'

Grancher::Task.new do |g|
  g.branch = 'gh-pages'
  g.push_to = 'origin' # automatically push too
  
  g.directory 'output'
end