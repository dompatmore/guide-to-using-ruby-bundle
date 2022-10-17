# To install rspec
## creates the Gemfile 
`bundle init`
​
## adds "rspec" to the Gemfile, but doesn't try to install it yet
`bundle add rspec --skip-install`
​
## creates a configuration file in .bundle that sets where we'll install gems to
`bundle config set --local path 'vendor/bundle'`
​
## downloads the gems' code into vendor/bundle (ready for us to use!)
`bundle install`
​
## make a folder for our specs
`mkdir spec/`
​
## create our first spec!
`touch spec/example_spec.rb`