# -*- ruby -*-

require "rubygems"
require "hoe"

Hoe.plugin :seattlerb
Hoe.plugin :rdoc
Hoe.plugin :isolate

Hoe.add_include_dirs "../../minitest/dev/lib"

Hoe.spec "minitest-gcstats" do
  developer "Ryan Davis", "ryand-ruby@zenspider.com"
  license "MIT"

  dependency "minitest", "~> 5.0"
  dependency "rake", "< 11", :developer
  dependency "minitest-proveit", "~> 1.0", :developer

  multiruby_skip << '1.8'
end

# vim: syntax=ruby
