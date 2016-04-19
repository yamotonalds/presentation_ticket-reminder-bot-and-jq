% バグ修正確認botの紹介とjq
% yamotonalds
% 2016-04-20

# 目次

## バグ修正確認bot

- 生まれた経緯
- 機能
- 気をつけたこと
- 結果

## jq

- jqとは
- 基本的な使い方
- 応用的な使い方？
- 実際のコード

# バグ修正確認botの紹介

## 生まれた経緯

. . .

元々オクダムbotがいた。

![](images/old_pivotal_bot.png)

. . .

⇒ 誰も見なかった。

##

エンジニアKPTのPに上げられた。

. . .

⇒ 個別にチケットを羅列すれば確認するのでは？(T)

##

Tになったけどエンジニアは忙しくて

（bot慣れしてなくて？）

作ってくれない…

. . .

🐼 > 定時後に作ろう

##

2016-03-23

. . .

バグ修正確認bot誕生

![](images/bot_birth.png)

##

2016-03-25

. . .

リマインド

![](images/remind-1.png)

##

2016-03-30

. . .

リマインド（2回目）

![](images/remind-2.png)

##

2016-03-31

. . .

初回華麗にバグる

![](images/bot_bug.png)

##

これには皆さんご立腹

![](images/planner_rage.png)

##

手動ではうまく行ってたのになぜ？

. . .

![](images/jq_is_here.png)

. . .

cron時にPATH通ってない `(^q^)`

##

改めて実行

![](images/bot_start.png)

##

早速ダメ出しを食らう

![](images/bot_dame.png)


##

和やかに話が弾む

<img src="images/bot_talk.png" height="600" />

##

まとまりそうにないなーと思ったそのとき

. . .

![](images/bot_talk2.png)

. . .

🐼 > なるほど？

##

バグ修正確認BOT希望記入シートが作られる

![](images/bot_hope_sheet.png)

. . .

みんなの投票はバラバラ

. . .

🐼 > やはり個別設定か

##

2016-04-07

. . .

個別設定で動き始める

![](images/bot_custom_start.png)


##

喜びの声

. . .

![](images/bot_custom_good.png)

##

要望も出てくる

![](images/bot_custom_request.png)


##

要望シートのグレードアップ

![](images/bot_custom_sheet_upgrade.png)

##

仕事に対する意欲向上

![](images/bot_custom_motivation.png)

##

2016-04-12

チケットをためていない場合にほめる機能実装

. . .

![](images/bot_custom_praise.png)

##

さり気なくアニメ化の宣伝も

![](images/bot_custom_new_game_anime.png)


##

2016-04-13

. . .

Redmineに対応

![](images/bot_custom_redmine.png)

優先度順表示も実装


##

水□くんの愛

![](images/bot_custom_mguchi_love.png)

. . .

（↑のリアクションは全部水□くんです）

##

2016-04-15

新たな仲間も加わり

![](images/bot_custom_ushijima.png)

##

バグ修正確認botはこれからも改良されながら

プロジェクトに貢献していきます 🐼

# ｊｑについて

##

思いの外botの話が長くなったので省略します `(^q^)`

. . .

時間があればbotのコードを少し眺めて終わりにしましょう。

