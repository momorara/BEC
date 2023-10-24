# BEC バッテリーエコキャンセル基板

<h4><<概要>></h4>
モバイルバッテリーでArduinoやRaspi-Pico、自作の電子回路を動作させた場合、バッテリーをつないでしばらくは動作するが、直ぐに電圧がゼロになり止まってしまいます。<br>
これは、モバイルバッテリーのeco機能で、低負荷時に電圧を切ってしまう機能が作動するからです。<br>
本基板はこの機能をキャンセルして、常時電圧を出力できるようにします。<br>

・LEDの色等指定はできません。<br>
・部品の仕様が変わる場合があります。<br>
・基板のバージョンが変わる場合がありますが、機能等にちがいはありません。<br>

<h4><<その他プロダクト>></h4>
・https://raspi.thebase.in/  <br>
お問い合わせは、HPからでも良いですし、pc_mailbox@mineo.jpでも構いません。

<h4><<エコ機能についての考察>></h4>
時間があったので、バッテリーのエコ機能について調べてみた。
・エコ機能の動作時間
　　　30秒から120秒までの幅があった。
・エコ機能をキャンセルするための負荷の印加時間　　
　　　　0.1秒から0.3秒の幅があった。
手持ちのバッテリー4種の結果なので、もっと幅があるかもしれないですね。
