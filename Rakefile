# frozen_string_literal: true

require 'html-proofer'

task :test do
  sh 'bundle exec jekyll build'
  options = {
    alt_ignore: [/.*/], # don't worry about images without an alt tag
    typhoeus: {
      ssl_verifypeer: false,
      ssl_verifyhost: 0
    }
  }
  HTMLProofer.check_directory('./_site', options).run
end
