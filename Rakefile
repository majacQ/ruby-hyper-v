require 'bundler'
Bundler.setup :rake
require 'jeweler'
$: << 'lib'
require 'hyper-v'

namespace :gem do
  Jeweler::Tasks.new do |s|
    s.name         = 'hyper-v'
    s.summary      = 'Admin stuff for Microsoft Hyper-V'
    s.description  = 'Admin stuff for Microsoft Hyper-V'
    s.email        = 'spraints@gmail.com'
    s.homepage     = 'http://github.com/spraints/hyper-v'
    s.files        = FileList['[A-Z]*', '{bin,lib,test}/**/*']
    s.version      = HyperV::VERSION
    s.add_dependency 'ruby-wmi'
  end
end
