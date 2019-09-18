# Catfe

Catfe is a React on Rails game like application that allow user to adopt cats through interaction. 
The source of inspiration for the app is from Neko Atsume. 

## Installation

```
bundle install
rails db:migrate && rails db:seed
rails s
```

## How to Use Catfe

Catfe is a simple game that allows user to use their given 100 gold to buy treats and feed a selected cat from a list. 
Each cat has a favorite treat that would accelerate the love meter more than other treats.
Once the love meter is filled, you succesfully adopted the cat.

## Developers
* Duong Nguyen  
* Rachel Rath

### License
This project is licensed under the Learn.co Educational Content License. Please read `LICENSE.md` location in the directory or click on the following link (http://learn.co/content-license) for further details.

## Built With
* Ruby version: 2.6.1
* [Ruby on Rails](https://github.com/rails/rails)
* [Rack CORS](https://github.com/cyu/rack-cors)
* [JWT](https://github.com/jwt/ruby-jwt)
* [BCrypt Ruby](https://github.com/codahale/bcrypt-ruby)
