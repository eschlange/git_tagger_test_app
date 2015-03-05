# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)

git_tagger = Gem::Specification.find_by_name "git_tagger"
load "#{git_tagger.gem_dir}/lib/tasks/deploy.rake"

Rails.application.load_tasks
