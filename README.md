Additional tidbits and side assignments
=======================================

End of Week 1
-------------

- For Mac users, setup a local rails environment: https://github.com/dougwig/bloc-extra/blob/master/mavericks.md
- Experiment with the use of the ".inspect" method, and how it can aid debugging. Open irb and try the following two lines:

```
    puts "second array = #{[1,2,3]}" 
    puts "second array = #{[1,2,3].inspect}" 
```
    
End of Week 2
-------------

- More on blocks: http://www.robertsosinski.com/2008/12/21/understanding-ruby-blocks-procs-and-lambdas/
- Meta-programming. Rails uses method_missing a lot for dynamic methods, like find_by_*.
Google "ruby method_missing". Now extend the String class so that it contains a dynamic method "get_N" that fetches the letter at index N.

```
    "hello".get_2 => 'l' 
    "hello".get_1 => 'e' 
```
    
- Make a gem. http://guides.rubygems.org/make-your-own-gem/

End of Week 3
-------------

- Research the HTTP protocol. Understand the different between GET, POST, PUT, and DELETE. Use curl to fetch http://www.google.com with headers.
- Research HTML forms, form variables, and submission.
- In db/seeds.rb, for every call to create or update_attributes, switch to the ! form of the method, so that errors are not silent.

End of Week 4
-------------

- You added image uploading via carrierwave. Convert bloccit to use carrierwave_direct instead, which allows image uploading without blocking your Heroku process for other users.
- Upgrade bloccit to rails version 4.

End of Week 5
-------------

- Experiment with rails composer. https://github.com/RailsApps/rails-composer

Awesome gems that you should check out:
-------------

- asset_sync
- better_errors
- carrierwave https://github.com/jnicklas/carrierwave
- cells https://github.com/apotonick/cells
- chef
- delayed_job / resque
- draper
- errbit
- eventmachine
- foreman
- geocoder
- letter_opener
- mechanize
- passenger
- prawn
- quiet_assets
- redcarpet
- stripe-ruby
- thor https://github.com/erikhuda/thor
- will_paginate
- vcr
- zeus https://github.com/burke/zeus
- https://github.com/YorickPeterse/ruby-lint
- https://github.com/troessner/reek
- http://watirwebdriver.com/
- http://activeadmin.info
- rails_admin
