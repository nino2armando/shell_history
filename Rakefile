# $LOAD_PATH handling not need if the standalone_migrations
# gem is installed
lib = File.expand_path("../../lib", __FILE__)

$:.unshift lib unless $:.include?(lib)

require "standalone_migrations"

StandaloneMigrations::Tasks.load_tasks


=begin
Dir["lib/tasks/**/*.rake"].each do |tasks|
  load tasks
end
=end


#task default: [:test]
