# coding: utf-8

require 'jekyll'


task :default => :serve

task :serve do
	jekyll('serve --incremental --watch')
end


def jekyll(args = '')
	sh 'jekyll ' + args
end
