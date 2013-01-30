require 'rake'  
require 'rspec/core/rake_task'
desc 'Default: run specs'
task :default => :spec

task :rebuild do
  `rm -fv ext/*.{o,bundle} ext/trie/*.{o,bundle} ext/Makefile ext/trie/Makefile`
  `cd ext/trie && ruby extconf.rb && make`
end


