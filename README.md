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

     $ rails migrate
     $ rails test
     $ rails server
