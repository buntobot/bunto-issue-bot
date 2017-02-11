require_relative 'bot'

task :travisci do
  print "It works!"
end

task :process_issues do
  Bunto::Bot.new.start(process: :issues)
end

task :process_prs do
  Bunto::Bot.new.start(process: :prs)
end
