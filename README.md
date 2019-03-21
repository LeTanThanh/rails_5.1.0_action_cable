# README
- Ruby 2.5.0
- Rails 5.1.0
- Bundler 1.17.3

- Run below commands for testing
```ruby
rails console
ActionCable.server.broadcast "web_notifications_channel", message: "Hello"
```
