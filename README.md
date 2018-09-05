# Rails Jumpstart

Rails Jumpstart Template but with a testing suite that includes:
- RSpec
- Cucumber
- Shoulda-Matchers
- Factory-bot
- database_cleaner
- rails-testing-controller

**Note:** Requires Rails 5.2

## Getting Started

Jumpstart is a Rails template, so you pass it in as an option when creating a new app.

#### Requirements

You'll need the following installed to run the template successfully:

* Ruby 2.5+
* bundler - `gem install bundler`
* rails - `gem install rails`
* Yarn - `brew install yarn` or [Install Yarn](https://yarnpkg.com/en/docs/install)

#### Creating a new app

```bash
rails new myapp -d postgresql -m https://raw.githubusercontent.com/seb-patron/jumpstart/master/template.rb
```

Or if you have downloaded this repo, you can reference template.rb locally:

```bash
rails new myapp -d postgresql -m template.rb
```

#### Cleaning up

```bash
rails db:drop
spring stop
cd ..
rm -rf myapp
```
