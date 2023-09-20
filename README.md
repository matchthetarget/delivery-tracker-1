# delivery-tracker-1

Target: https://delivery-tracker-1.matchthetarget.com

```
rails generate draft:resource delivery supposed_to_arrive_on:date arrived:boolean description:string details:text user_id:integer
```

```
rails generate devise:install
```

```ruby
# config/initializers/devise.rb, Line 269

config.sign_out_via = :get
```

```
rails generate devise user
```
