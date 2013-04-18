namespace :sass do
  desc "Converts SCSS or Sass files to CSS."
  task :compile do
    sh "bundle exec compass compile"
  end

  desc "Remove generated files and the sass cache."
  task :clean do
    sh "bundle exec compass clean"
  end
end