desc 'Start jekyll server'
task :server do
  `bundle exec jekyll server --watch`
end

task default: :server

namespace :assets do
  task :precompile do
    puts `bundle exec jekyll build`
  end
end
