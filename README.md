Had a problem with Devise set up => I can't use bcrypt on Apple M1 Chip

Got this solved by first uninstalling bcrypt with gem uninstall bcrypt, then bundle install (or gem install bcrypt)
