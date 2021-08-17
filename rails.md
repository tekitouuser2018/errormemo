

## You've tried to invoke Spring when it's already loaded (i.e. the Spring constant is defined).
## This is probably because you generated binstubs with Spring 1.0, and you now have a Spring version > 1.0 on your system. To solve this, upgrade your bundle to the latest Spring version and then run `bundle exec spring binstub --all` to regenerate your binstubs. This is a one-time step necessary to upgrade from 1.0 to 1.1.

https://www.fixes.pub/program/325468.html

This ERROR message may doesn't show actual reason for ERROR.
And you need to delete Spring and execute rails command , so actual ERROR message shows.



## rails db:migrate, db:setup

IF
rails aborted!
ActiveRecord::RecordInvalid: バリデーションに失敗しました
=>
rails db:migrate:reset

https://teratail.com/questions/178254

## Webpacker::Manifest::MissingEntryError

> brew install yarn

で解消した

https://qiita.com/masatwork/items/1b5d190cc76f5eeffbb7

https://qiita.com/GalaxyNeko/items/630ac869d3bbbe93034b

## ActionController::InvalidAuthenticityToken

> protect_from_forgery

を追記

https://qiita.com/_ayk_study/items/88269643c675fd4ca975
