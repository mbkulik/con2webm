task :default => [:install]

prog="con2webm"

task :install do
     FileUtils.cp prog, "#{Dir.home}/bin"
end

task :uninstall do
     FileUtils.rm "#{Dir.home}/bin/#{prog}"
end
