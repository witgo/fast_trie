require 'rubygems'
require 'rake'
desc 'run rebuild'
task :rebuild do
  `rm -fv ext/*.{o,bundle} ext/trie/*.{o,bundle} ext/Makefile ext/trie/Makefile`
  `cd ext/trie && ruby extconf.rb && make`
end


