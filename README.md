# Rails + Sass + Bootstrap
```
Bootstrapを用いて、割と簡単に動的ウェブサイトを構築できるフォーマットになってると思います。
```

| 日付| Ver | 内容 |
|:-:|:-:|:-:|
|180720|v1.0.0|Rails + Sass + Bootstrapの基盤フォーマット|


# 前提
- rbenv
- bundler

# 起動
``` shell
- bundle install
- cp .env.sample .env # 環境変数を記載
- bundle exec rails db:create
- bundle exec rails db:migrate
- bundle exec rails s
```
