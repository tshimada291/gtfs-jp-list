# gtfs-jp-list
日本国内で公開されている「標準的なバス情報フォーマット」およびGTFSのオープンデータ一覧です。

## URL
* GTFS / GTFS-JP (static data list)
  * https://tshimada291.github.io/gtfs-jp-list/gtfs-jp-list.csv 
* GTFS-RT (realtime data list)
  * https://tshimada291.github.io/gtfs-jp-list/gtfs-rt-list.csv

## License
[Creative Commons — CC0](https://creativecommons.org/publicdomain/zero/1.0/)
* [CC0について (Creative Commons Japan)](https://creativecommons.jp/sciencecommons/aboutcc0/)

## Attribute
* 静的データリスト
  * official：公式・公認のデータであれば1、個人等による作成データの場合は0としています。
  * fixed_url：配信元のzipデータURLが固定URLであれば1、なければ0としています。（直近の状況をみて指定しているため、変わる場合があります。）
  * api_key：APIキーが必要であれば1、なければ0としています。
* 動的データリスト
  * rt_api_key：APIキーが必要であれば1、なければ0としています。
  * interval_sec：データ更新間隔を秒単位で記してあります。（配信サイトに記載ない場合は空欄としています。）

## Notice
* 静的データリストの更新はおおむね1週間に1回を予定しています。
  * 動的データリストについては不定期となります。 
* 試験公開につき、ファイルの内容について項目名などを変更する場合があります。

## History
2021.3.5　掲載開始

## External links
* [GTFS・「標準的なバス情報フォーマット」オープンデータ一覧](https://tshimada291.sakura.ne.jp/transport/gtfs-list.html)
* [GTFS.JP](https://www.gtfs.jp/)
