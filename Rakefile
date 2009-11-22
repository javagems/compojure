require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "compojure"
    gem.summary = %Q{A JavaGem packaged version of Compojure}
    gem.description = %Q{The Compojure web framework}
    gem.email = "gabriel@javagems.org"
    gem.homepage = "http://github.com/javagems/compojure"
    gem.authors = ["gabrielg"]
    gem.add_dependency "clojure"
    gem.add_dependency "clojure-contrib"
    gem.add_dependency "jetty"
    gem.add_dependency "jetty-util"
    gem.add_dependency "commons-fileupload"
    gem.add_dependency "commons-codec"
    gem.add_dependency "commons-io"
    gem.add_dependency "servlet-api"
  end
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: sudo gem install jeweler"
end

task :default => :build
