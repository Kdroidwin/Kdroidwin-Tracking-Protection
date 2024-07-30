# Kdroidwin Tracking Protection
これはアプリ版AdGuard向けのトラッキング防止フィルターです。どのアプリが対応しているかはフィルターを直接みてください。
極力不具合は避けていますが、AdGuard公式がリストインしないだけあってか、多少不具合は被ります。無駄な通信もカットします。

# フィルター追加方法

```
https://raw.githubusercontent.com/Kdroidwin/Kdroidwin-Tracking-Protection/main/adguard_user_rules_2207_103417.txt
```
上記リンクをAdGuardアプリの⚙アイコン>フィルタリング>フィルタ>カスタムフィルタからカスタムフィルターに追加

uBlockoriginの場合はAdGuard専用のルールが使われているため、フィルターを改変する必要があります。(目のアイコンで確認可能)


# 補足


||static.line-scdn.net^$app=jp.naver.line.android
を追加するとアンケートやスタンプ購入などのLINEのほとんどの機能(基本的なトークは可能)は使えないがトラッキングは減らせる。


# 既知の不具合 
- LINE Facebook関連の機能が使えない
- LINE 初回ログインができないときがある
- LINEのマップ機能は動作しない
- LINEのプロフィール画像が見れない
 (uts-front.line-apps.com  profile.line-scdn.net)

(これらの通信はトラッキングが含まれるので修正しない)

# 他にも
おすすめのリポジトリ
[uBlacklistのフィルター](https://github.com/Kdroidwin/uBlacklist-filter-by-kdroidwin?tab=readme-ov-file)

# 連絡先
[Twitter](https://x.com/Kdroidwin1)
[ブログ](kdroidwin.hatenablog.com)

