## Factory not registered
factory bot をリロードする処理を作成する。

※config.before(:all)だとrubocopに怒られたため、下記のように修正

```
 RSpec.configure do |config|
  config.before do
    FactoryBot.reload
  end
 end
```

https://matazoukun.hatenablog.com/entry/2020/09/22/144736
