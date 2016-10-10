# SYNOPSIS
     make [migrate | test | server]

# OPTIONS
     migrate
             rails db:migrate:reset db:seed
     test
             rails test
     server
             rails server -b 0.0.0.0

# EXAMPLES

First, save the Makefile into your Rails project folder. Then, you can run the following commands from within that folder.

     $ rails migrate
     $ rails test
     $ rails server
