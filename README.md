# gtfs-jp-list
日本国内で公開されている「標準的なバス情報フォーマット」およびGTFSのオープンデータ一覧です。

## Caution
**当リストに掲載しているデータの品質は保証していません。** 現在、一部のGTFS/GTFS-JPオープンデータ・公開データについて不正確なデータが掲載されている事例が確認されています。 **正確性を要する時刻表アプリや経路検索アプリへの利用やその他商用・有償サービスでの利用、あるいは研究目的の利用を検討している場合は、以下の点について十分に確認のうえ、利用目的にそぐわないデータについては利用を控えるようお願いいたします。**（可能であれば、データ提供元（feed_publisher）への連絡・情報提供をお願いいたします。）
* **データの有効期限切れ**（feed-info.txtのfeed_end_date（無い場合はcalendar.txtのend_date、またはcalendar_dates.txtの最後の日付）が期限を過ぎている（リストに掲載あり）） 
  * ダイヤ改正に対応できていない可能性があります。
  * ダイヤ改正がなく期限更新のみされていない（データ提供元が期限の更新を失念している）場合もあります。
* **停留所・標柱情報（stops.txt）の位置情報が不正確**
  * のりばの位置が本来の位置を示さずに、ある1か所（道路の真ん中、交差点の真ん中など）に重なっている
* **最新のダイヤに対応していない**
  * ダイヤ改正以降も古いダイヤ情報が残っており、廃止日以降に指定検索した場合でも表示されてしまう場合があります。
    * アーカイブとして残されている過去データについては該当しません。

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
