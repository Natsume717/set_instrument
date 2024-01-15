# set_instrument
item_modifiersのset_instrumentに関するデータパックサンプルになります。

詳しくはブログ記事『[【マイクラ】コマンドで角笛の音色を変更する【item_modifiers】](https://natsumake.com/command_horn/)』を参考にしてください。

<h3>使い方</h3>

```/item modify entity @s weapon.mainhand sample:test```で手に持っている角笛の音色を、全種類の中からランダムに変更。

```/item modify entity @s weapon.offhand sample:original_tag```を実行することで、original_tag.jsonで指定した音色の中からランダムに変更する。<br>
（本サンプルの場合は1種類のみを指定しているため、「感覚」の音色となります）
