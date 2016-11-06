# E-commerce shop page

## Web page for e-commerce with Camaleon cms
#### http://camaleon.tuzitio.com
### Using rails -v 5.0.0.1 and ruby 2.3.0
### Main installation:
For installation download with next command:``` git clone https://github.com/Bratela/test_shop.git``` to local folder.
And run ``` bundle install ```.
After run ``` rake db:migrate ```.
And run ``` rails s ``` for start server.

### E-Commerce plugin installation!
Add to gemfile ``` gem 'camaleon_ecommerce', github:  'owen2345/camaleon-ecommerce' ```.
And run ``` bundle install ```.
After run ```rake db:migrate ```.
Go to activate E-Commerce plugin in http://localhost:3000/admin/plugins
