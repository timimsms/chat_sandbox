# Chat Sandbox 🏖

Small Rails project to experiment with various chat and conversational user experiences.

## Development

### Local Setup

To get started:

- Create new PostgreSQL user: chat_sandbox_development_admin via running `create role chat_sandbox with createdb login password 'ChatMeUp2019';` in psql.
- Setup the database using `bundle exec rake db:create && bundle exec rake db:migrate`.
- Run `rails server` to start the web application.

## Resources

- https://pusher.com/tutorials/chat-app-ruby-rails
