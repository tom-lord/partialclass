require "bundler/gem_tasks"
require "rake/testtask"

Rake::TestTask.new do |t|
	t.libs << "test/common"
	t.test_files = FileList['test/test_*.rb']
	t.verbose = false
end
