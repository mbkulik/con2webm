task :default => [:install]

task :install do
	FileUtils.cp "con2webm", "#{Dir.home}/bin"
end

task :uninstall do
	FileUtils.rm "#{Dir.home}/bin/con2webm"
end
