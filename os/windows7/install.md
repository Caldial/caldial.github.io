# Windows7 インストール

このページでは`Windows7 Professional SP1`のインストールについて解説します。

OSのディスクを入れると`Windows is loading files...`と表示されるのでしばらく待ちます。

![img](img/win7_001.png "img")

![img](img/win7_002.png "img")

![img](img/win7_003.png "img")

「次へ」を押します。

![img](img/win7_005.png "img")

「今すぐインストール」を押します。

![img](img/win7_006.png "img")

![img](img/win7_007.png "img")

「同意します」にチェックを入れて「次へ」を押します。

![img](img/win7_008.png "img")

「新規インストール」を押します。

![img](img/win7_010.png "img")

「ドライブオプション」を開き、新しいパーティションを作成します。 

![img](img/win7_011.png "img")

レガシーBIOSモードの場合、以下のパーテションが自動で作成されます。
|名前|合計サイズ|種類|
|----|----|----|
|パーティション1(システムで予約済み)|100MB|システム|
|パーティション2|残り|プライマリ|

UEFIブートの設定が有効の場合、以下のパーテションが自動で作成されます。  
UEFIブートはレガシーBIOSモードと異なり、2TB以上のHDDをブートHDDに利用可能、対障害性が向上するなどのメリットがあるため、UEFIブートを推奨します。

|名前|合計サイズ|種類|
|----|----|----|
|パーティション1|100MB|システム|
|パーティション2|128MB|MSR(予約済み)|
|パーティション3|残り|プライマリ|

![img](img/win7_012.png "img")

インストールが開始されます。何度かPCの再起動が実行されます。

![img](img/win7_013.png "img")

コンピュータの再起動を促されます。  
15秒間そのままにするか、［Enter］を押すと再起動します。 

![img](img/win7_014.png "img")

Windows7のロゴが表示されます。  
この画面が表示されずに最初の黒画面が表示される場合、コンピュータのドライブ読み込み順がディスク優先に設定されています。その場合はBIOSで読み込み順をドライブ優先に再設定してください。

![img](img/win7_016.png "img")
![img](img/win7_017.png "img")
![img](img/win7_018.png "img")
![img](img/win7_019.png "img")
![img](img/win7_020.png "img")
![img](img/win7_021.png "img")

ユーザー名を設定します。  
日本語名も利用可能ですが、一部プログラムが正しく動かないなどの情報もあるため、英数字を推奨します。

![img](img/win7_023.png "img")

パスワードを設定します。

![img](img/win7_024.png "img")

プロダクトキーの入力を促されますが、「次へ」を押してスキップします。  
この後の設定でハードウェア構成が大きく変更されたり、OSを再インストールする事態になった場合に再アクティベーションが必要になってしまうため、プロダクトキーの入力はOSやドライバーのインストールが一段落した段階で入力します。

![img](img/win7_025.png "img")

「後で設定します」を選択します。  
 最初のWindowsUpdateは手動で行うためです。  
 自動を選択すると手動アップデートが自動アップデートと競合して上手くできない場合があります。

![img](img/win7_026.png "img")

「次へ」を押します。

![img](img/win7_027.png "img")

「社内ネットワーク」を選択します。  
自宅で利用する場合でも「社内ネットワーク」を推奨します。  
「ホームネットワーク」との違いは標準でホームグループが動作するかどうかになります。
余計なサービスは稼働させたくないので「社内ネットワーク」で問題ありません。

![img](img/win7_028.png "img")
![img](img/win7_031.png "img")
![img](img/win7_032.png "img")

これでOSインストールは完了です。  

![img](img/win7_033.png "img")

[目次に戻る](../index.md)