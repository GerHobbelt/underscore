desc "Use Uglify JS to compress Underscore.js"
task :build do
  sh "node_modules/uglify-js/bin/uglifyjs underscore.js -c \"evaluate=false\" --comments \"/    .*/\" -m -o underscore-min.js"
end

desc "Build the docco documentation"
task :doc do
  sh "node_modules/docco/bin/docco underscore.js"
end

