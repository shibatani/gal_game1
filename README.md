# name
Gal Game

# description
主人公がヒロインのために奮闘するゲームです。
エンターキーを押すと物語が進んでいきます。
ゲームバランスがガバガバで、イベント数が少ないのでもう少し改良していきます（汗)

# fire structure
このアプリは以下のファイルで構成されています。
* main.rb -> 実行プログラム
* boy.rb -> 主人公のデータ、コマンド
* girl.rb -> ヒロインのデータ
* games_controller.rb -> ゲーム稼働に関するコマンド
* message_boy.rb -> イベント関連のメッセージを出力するモジュール
* message_controller.rb -> ゲーム稼働関連メッセージを出力するモジュール


# how to use
```
(a) ruby main.rb で起動。
(b) main.rbで主人公、ヒロインの名前をお好みの名前に変更
(b) 運に任せてエンターキーを押し続ける。
(c) 主人公とヒロインが結婚すればゲームクリア。
(d) 主人公がフラれるとゲームオーバー。
```

