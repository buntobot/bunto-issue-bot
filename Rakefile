require_relative 'bot'

task :process_issues do
  Bunto::Bot.new.start(process: :issues)
end

task :process_prs do
  Bunto::Bot.new.start(process: :prs)
end
