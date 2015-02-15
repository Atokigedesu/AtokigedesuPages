+++
date      = "2015-02-14T22:41:01+09:00"
draft     = true
title     = "判定動画作成スクリプト"
thumbnail = "/images/hitbox-video-thumb.png"
+++

[こちらの攻撃判定データの全画像化プロジェクト](http://smashboards.com/threads/stratocasters-hitbox-system-new-download-link.283973/)が面白そうだったので動画化するスクリプト作りました。

出力はこんな感じ  
<video src="/videos/hitbox-generation-sample.mp4" controls loop>

<script src="https://gist.github.com/Atokigedesu/39243a406abc56f7213e.js"></script>

上のプロジェクトのリンクから`New Hitboxes.zip`をダウンロードしてきて、上のスクリプトを zip と同じディレクトリで実行すると使えます。

![ダウンロード場所](/images/how-to-download-all-hitbox-images.png)

以前作った [HTML5 video タグを 1 フレーム単位で再生するこれ](/HitboxSlider/)と組み合わせてうにょうにょしたいなーとか。

これ、Mac で作ったけど Linux でも動くんじゃないかな。ある程度はしっかりつくりました。
ただ、まあ、元データの命名規則がバラバラなので上手く動画化されないキャラもいます……。
