# Kdroidwin-Tracking-Protection
これはAdGuardやuBlock Origin向けのトラッキング防止フィルターです。
極力不具合は避けていますが、AdGuard公式がリストインしないだけあってか、多少不具合は被ります。

# フィルター追加方法

```
https://raw.githubusercontent.com/Kdroidwin/Kdroidwin-Tracking-Protection/main/adguard_user_rules_2207_103417.txt
```
上記リンクをAdGuardアプリの⚙アイコン>フィルタリング>フィルタ>カスタムフィルタからカスタムフィルターに追加

uBlockoriginの場合はフィルターリスト>インポートから


# 補足


||static.line-scdn.net^$app=jp.naver.line.android
を追加するとアンケートやスタンプ購入などのLINEのほとんどの機能(基本的なトークは可能)は使えないがトラッキングはかなり減らせる。

他にもおすすめのリポジトリ
[uBlacklistのフィルター](https://github.com/Kdroidwin/uBlacklist-filter-by-kdroidwin?tab=readme-ov-file)

- 既知の不具合
LINE Facebook関連の機能が使えな
