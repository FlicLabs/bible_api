task :deploy do
  sh "rsync -az ./ deploy@bible-api.empowerverse.org:/var/www/apps/bible_api/ && ssh deploy@bible-api.empowerverse.org 'cd /var/www/apps/bible_api && bundle install && touch tmp/restart.txt'"
end
