# Chat Sandbox 🏖

Small Rails project to experiment with various chat and conversational user experiences.

## Development

### Local Setup

To get started:

- Create new PostgreSQL user: chat_sandbox_development_admin via running `create role chat_sandbox_development_admin with createdb login password '<password>'` in psql (where `<password>` would be replaced with a password that you set).
- Setup the database using `bundle exec rake db:create && bundle exec rake db:migrate`.
- Run `rails server` to start the web application.
