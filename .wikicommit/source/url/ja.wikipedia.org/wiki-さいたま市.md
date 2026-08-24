---
source:
  type: url
  url: 'https://ja.wikipedia.org/wiki/さいたま市'
  hash: sha256:05053e26b3f5a9025d0ab11a77f65d92407b3b33b6f77426076b51203bf76479

schema:
status: generated
last_generated_at: "2026-08-24"
extracted_tokens: 105754
generated_pages:
  - .wikicommit/entity/ja/AdministrativeArea/saitama-city.md
  - .wikicommit/entity/ja/AdministrativeArea/nishi-ward.md
  - .wikicommit/entity/ja/AdministrativeArea/kita-ward.md
  - .wikicommit/entity/ja/AdministrativeArea/omiya-ward.md
  - .wikicommit/entity/ja/AdministrativeArea/minuma-ward.md
  - .wikicommit/entity/ja/AdministrativeArea/chuo-ward.md
  - .wikicommit/entity/ja/AdministrativeArea/sakura-ward.md
  - .wikicommit/entity/ja/AdministrativeArea/urawa-ward.md
  - .wikicommit/entity/ja/AdministrativeArea/minami-ward.md
  - .wikicommit/entity/ja/AdministrativeArea/midori-ward.md
  - .wikicommit/entity/ja/AdministrativeArea/iwatsuki-ward.md
  - .wikicommit/entity/ja/StadiumOrArena/saitama-stadium-2002.md
  - .wikicommit/entity/ja/StadiumOrArena/saitama-super-arena.md
  - .wikicommit/entity/ja/StadiumOrArena/nack5-stadium-omiya.md
  - .wikicommit/entity/ja/SportsTeam/urawa-red-diamonds.md
  - .wikicommit/entity/ja/SportsTeam/rb-omiya-ardija.md
  - .wikicommit/entity/ja/Place/hikawa-shrine.md
  - .wikicommit/entity/ja/Place/tsuki-shrine.md
  - .wikicommit/entity/ja/Place/omiya-park.md
  - .wikicommit/entity/ja/Place/railway-museum.md
  - .wikicommit/entity/ja/Place/omiya-bonsai-art-museum.md
  - .wikicommit/entity/ja/Place/iwatsuki-doll-museum.md
  - .wikicommit/entity/ja/Place/saitama-shintoshin.md
  - .wikicommit/entity/ja/Place/minuma-tsusenbori.md
  - .wikicommit/entity/ja/Place/tajimagahara-primrose-habitat.md
  - .wikicommit/entity/ja/DefinedTerm/iwatsuki-dolls.md
  - .wikicommit/entity/ja/DefinedTerm/omiya-bonsai.md
  - .wikicommit/entity/ja/DefinedTerm/urawa-unagi.md
failed_pages: []
---

## Summary

日本語版Wikipediaの「さいたま市」記事。埼玉県の県庁所在地であり政令指定都市であるさいたま市について、2001年の浦和市・大宮市・与野市の合併と2005年の岩槻市編入という成立経緯、10行政区の区分と人口・面積・区の色/区の花、地理・気候・歴史、行政組織、経済、教育、文化施設、スポーツ、観光資源、交通網までを網羅的に記述している。市内の主要な神社仏閣・博物館・スタジアム・プロスポーツクラブと、それぞれの所在区との対応関係が体系的に示されており、テーマの中核である「10区の地理・歴史」と「区内の主要施設・組織とその所在区との関係」に直接対応する。なお、市が提供する行政手続き（ごみの出し方、住民異動届等の窓口業務）については本ソースに実質的な記述がなく、エンティティを抽出していない。

テーマ不一致により除外したエンティティ:
- 「しまむら」ほか市内に本社を置く一般企業: テーマが対象とする「区内の主要施設・組織（神社仏閣、博物館、スタジアム、スポーツクラブ等）」に該当せず、単なる本社所在地の列挙にとどまるため
- 「呪術廻戦」ほか「さいたま市を舞台とした作品」の各作品: 創作作品であり、市の地理・歴史・施設・行政手続きを扱うテーマの対象外

schema の properties に受け皿がなく本文にのみ記載した情報（coverage_gap_note）:
- 「さいたま市」および10区の各ページ: 市町村コード・人口・面積・人口密度・区の色・区の花・設置日が AdministrativeArea.md の properties フィールドに対応する項目を持たないため、本文にのみ記載した
- 「浦和レッズ」「RB大宮アルディージャ」: AFCチャンピオンズリーグ優勝回数やJリーグオリジナル10といった競技実績・称号が SportsTeam.md の properties に受け皿がないため、本文にのみ記載した
- 「武蔵一宮氷川神社」「見沼通船堀」「田島ヶ原サクラソウ自生地」: 社格（武蔵国一宮）・開削年・文化財指定区分（国の史跡、国の特別天然記念物、埼玉県指定有形文化財）が Place.md の properties に受け皿がないため、本文にのみ記載した
