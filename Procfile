web: bundle exec rails server -p $PORT
web: bundle exec puma -C config/puma.rb
release: bundle exec rails db:migrate && bundle exec rails db:seed