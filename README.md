rp-cap-test
===========

Testing out capistrano v3 for railsplayground

The process to generate the capistrano deploy error is as follows:

1) Created github repo: https://github.com/schenkman/rp-cap-test
2) Cloned repo and created blank rails application and commited files
2) Enable capistrano in the gemfile (simply uncommented it)
3) Run "cap install" and commit files
4) Edit files for a deploy to railsplayground
- Check changes in config/deploy.rb and config/deploy/staging.rb
5) Run "cap deploy:checK" and see error
