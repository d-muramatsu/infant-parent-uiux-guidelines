# 出典と適用限界

確認日：2026-11-14。検索結果だけでなく以下の公開本文を確認した。原文の翻訳転載ではなく短い要約と独立した設計提案を用いている。

| ID | 出典・読んだ範囲 | 利用した内容 | 限界 |
|---|---|---|---|
| A | [AAP: Screen Time for Infants](https://www.aap.org/en/patient-care/media-and-children/center-of-excellence-on-social-media-and-youth-mental-health/qa-portal/qa-portal-library/qa-portal-library-questions/screen-time-for-infants/) の回答、Watching TV or Streaming Videos、Resources for Parents | 乳児の画面利用を抑え、共に見て、現実の遊びを置き換えないという利用方針 | UI仕様書ではない。相関を因果や個人への診断に変換しない。特定アプリの教育効果を保証しない |
| Z | [ZERO TO THREE: Screen-Use Tips for Parents of Children Under Three](https://www.zerotothree.org/resource/screen-use-tips-for-parents-of-children-under-three/) の本文2節 | 会話、実物の遊びとの接続、余計な演出や背景メディアへの注意 | 2024-10-25掲載。3歳未満を含む幅広い助言で、各項目が乳児の単独操作を推奨するわけではない |
| E | [ETSI EG 202 423 V1.1.1](https://www.etsi.org/deliver/etsi_eg/202400_202499/202423/01.01.01_60/eg_202423v010101p.pdf) の目次、§5、Table 1（印刷頁44〜45付近） | 年齢・身体的特性を考慮し、そもそも機器利用が適切か検討する設計の視点 | 2005-10の資料。本書の現代スマホ仕様の根拠として全面採用しない。資料内の“Infants”は4〜7歳の分類なので、日本語の「乳児」と同一視しない。全77頁の精査済みとはしていない |
| U | [UNICEF Innocenti: Children’s Best Interests in Digital Policy and Practice](https://www.unicef.org/innocenti/reports/childrens-best-interests-digital-policy-and-practice) の公式概要 | 子どもの利益、包摂性、子ども中心の設計という上位原則 | 2026-04公表。概要のみ確認し、PDF全体の精査は未実施。参加調査の知見を乳児の操作能力の実証としない |
| W | [W3C: WCAG 2.2](https://www.w3.org/TR/WCAG22/) の適用範囲・達成基準、特に2.5.5と2.5.8 | 一般Webアクセシビリティ、操作対象サイズの基準とレベルの区別 | 乳児専用基準ではない。44pxは乳児向け実証値ではない。個別製品の適合宣言には該当基準の全体評価が必要 |

## 本書の独自提案

無音開始、広告なし、複数指・連打時の抑制、親子画面の分離、終了を促す文言、保存しない選択肢、親向けレビュー手順は、この文脈への設計提案。各団体がこの仕様をそのまま要求しているという意味ではない。

## 採用しない読み替え

- 幼児向けの時間目安を、11か月の子の「安全時間」に変えない。
- 「高品質」「インタラクティブ」を名乗れば長時間利用してよい、としない。
- 凝視やタップ回数から学習・発達・満足度を判定しない。
- 親向けの便益と子ども本人の便益を混同しない。
- 古い発達理論の説明を、最新の医学的事実として再掲しない。

## 改訂時に残す記録

確認日、資料の版・更新日、確認箇所、変更した項目、変更理由、未確認事項を記す。リンクが読めなかった場合は「確認済み」としない。
