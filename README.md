# BEC バッテリーエコキャンセル基板 (V1 , V2)

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
時間があったので、バッテリーのエコ機能について調べてみた。<br>
・エコ機能の動作時間<br>
　　　30秒から120秒までの幅があった。<br>
・エコ機能をキャンセルするための負荷の印加時間　　<br>
　　　0.1秒から0.3秒の幅があった。<br>
手持ちのバッテリー4種の結果なので、もっと幅があるかもしれないですね。<br>
2024/1/19 最近AOKUSの【2023極薄モデル·20000mAh大容量】を購入しました。<br>
なんと、エコ機能が8秒程で働くようで、これには参りました。<br>
このような機種にはBECは使えないですね...<br>

<h4><<基板バージョンについて>></h4>
🔳基板のバージョン 〜v04までのもの(V1と呼称します)<br>
　　リセットICによる制御を行っています。<br>
  　約17秒毎に、約1秒間負荷を掛けます。<br>
  　周期は変更できません。<br>
  　負荷は約94mA、約116mA、約151mAが選択できます。<br>
    ・部品調達の関係で販売終了しています。
🔳基板バージョン v05以降のもの(V2と呼称します)<br>
　　タイマーICによる制御を行っています。<br>
  　約38秒毎に、約0.7秒間負荷を掛けます。<br>
  　周期は変更できません。<br>
  　負荷は約75mA、約150mAが選択できます。<br>
