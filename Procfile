web: bundle exec puma -C config/puma.rb
resque_worker: env TERM_CHILD=1 RESQUE_TERM_TIMEOUT=8 QUEUE=high,medium,low bundle exec rake resque:work
