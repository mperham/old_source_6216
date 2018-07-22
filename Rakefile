task :s do
  system("ruby -rwebrick -e 'WEBrick::HTTPServer.new(:Port=>4000,:DocumentRoot=>\"./gems\").start'")
end

task :gen do
  system("gem generate_index --directory ./gems")
end
