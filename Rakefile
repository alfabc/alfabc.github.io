require 'jekyll'

task default: %w[test]

task :test do
  options = Hash.new
  options["serving"] = false
  Jekyll::Commands::Build.process(options)
end
