require "bundler/gem_tasks"

desc 'Download fresh js from GH'
task :download_js do
  `wget https://raw.githubusercontent.com/aFarkas/lazysizes/master/lazysizes.js -O vendor/assets/javascripts/lazysizes_rails.js`
  `wget https://raw.githubusercontent.com/aFarkas/lazysizes/master/lazysizes.min.js -O vendor/assets/javascripts/lazysizes_rails.min.js`
end

