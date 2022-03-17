# base_ruby_on_rails

https://qiita.com/yuitnnn/items/b45bba658d86eabdbb26

以下を行う。

```
bundle init
```

Gemnfile 内の以下の箇所をcomment in する。

```
gem "rails"
```

Railsをインストール

```
bundle install --path vendor/bundle
```


プロジェクトの生成

Mysqlを採用する場合

```
bundle exec rails new . -B -d mysql --skip-turbolinks --skip-test
```

必要なライブラリがあれば、Gemfile を編集して以下を行う。

```
bundle install
```


This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
