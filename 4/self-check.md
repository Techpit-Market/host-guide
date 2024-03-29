# 4-9 レビューを依頼する前のセルフチェック

執筆スタイルガイド通りに従って教材を執筆したら、Techpitの編集チームが教材をレビューします。*レビューは章ごとに行います。*

カリキュラムの提出の前に以下のチェック項目を満たしているか確認してください。

## TextLintの実行
一般的な日本語の構文チェックに加え、Techpitのスタイルガイドに記載されているルールの一部をTextLintでチェックすることができます。
使用方法やTextLintでチェック可能なルールなど、詳細は[TextLintのリポジトリ](https://github.com/Techpit-Market/curriculum-textlint)をご確認ください。

{% hint style="info" %}
もしTextLintに対する改善要望や不具合報告などありましたら、[TextLintのリポジトリ](https://github.com/Techpit-Market/curriculum-textlint)にIssueもしくはPRを起票くださると助かります。
{% endhint %}

## Must (この項目の確認後レビュー提出をお願いします。)
### 全体
- [ ] **教材で達成したい目的を満たしている** [(詳細)](https://techpit-market.gitbook.io/host-guide/4/4-1#2-deshitaiwotashiteiruka)
- [ ] 見出しは1ページ1つのみ使用している [(詳細)](https://techpit-market.gitbook.io/host-guide/4/markdown#1-shinoi)
- [ ] 外部サイトを利用する箇所では、操作する箇所を強調したスクリーションショットを使って操作方法を説明している [(詳細)](https://techpit-market.gitbook.io/host-guide/4/4-6#2-nosukurnshottowo)
- [ ] [GitHubの運用に関して](https://techpit-market.gitbook.io/host-guide/4/4-5)を一読した

### 0章について
- [ ] 教材の学習後の姿が記載されている [(詳細)](https://github.com/Techpit-Market/curriculum-format/blob/master/0%E7%AB%A0%E3%81%AE%E3%83%95%E3%82%A9%E3%83%BC%E3%83%9E%E3%83%83%E3%83%88/0-1%20%E6%95%99%E6%9D%90%E3%81%AE%E6%A6%82%E8%A6%81.md#%E6%9C%AC%E6%95%99%E6%9D%90%E3%81%8C%E7%B5%82%E3%81%88%E3%81%9F%E3%82%89%E3%81%A9%E3%81%AE%E3%82%88%E3%81%86%E3%81%AA%E7%8A%B6%E6%85%8B%E3%81%AB%E3%81%AA%E3%81%A3%E3%81%A6%E3%81%84%E3%82%8B%E3%81%8B)
- [ ] 学習に必要な前提知識が記載されている [(詳細)](https://github.com/Techpit-Market/curriculum-format/blob/master/0%E7%AB%A0%E3%81%AE%E3%83%95%E3%82%A9%E3%83%BC%E3%83%9E%E3%83%83%E3%83%88/0-1%20%E6%95%99%E6%9D%90%E3%81%AE%E6%A6%82%E8%A6%81.md#%E5%8F%97%E8%AC%9B%E3%81%AB%E3%81%8A%E3%81%91%E3%82%8B%E5%BF%85%E8%A6%81%E6%9D%A1%E4%BB%B6)
- [ ] 教材の対象者が記載されている [(詳細)](https://github.com/Techpit-Market/curriculum-format/blob/master/0%E7%AB%A0%E3%81%AE%E3%83%95%E3%82%A9%E3%83%BC%E3%83%9E%E3%83%83%E3%83%88/0-1%20%E6%95%99%E6%9D%90%E3%81%AE%E6%A6%82%E8%A6%81.md#%E3%81%93%E3%81%AE%E6%95%99%E6%9D%90%E3%81%AE%E5%AF%BE%E8%B1%A1%E8%80%85)
- [ ] 教材で学ばないことが記載されている [(詳細)](https://github.com/Techpit-Market/curriculum-format/blob/master/0%E7%AB%A0%E3%81%AE%E3%83%95%E3%82%A9%E3%83%BC%E3%83%9E%E3%83%83%E3%83%88/0-1%20%E6%95%99%E6%9D%90%E3%81%AE%E6%A6%82%E8%A6%81.md#%E5%AD%A6%E3%81%B0%E3%81%AA%E3%81%84%E3%81%93%E3%81%A8)
- [ ] 教材で利用する技術のバージョンが記載されている [(詳細)](https://github.com/Techpit-Market/curriculum-format/blob/master/0%E7%AB%A0%E3%81%AE%E3%83%95%E3%82%A9%E3%83%BC%E3%83%9E%E3%83%83%E3%83%88/0-1%20%E6%95%99%E6%9D%90%E3%81%AE%E6%A6%82%E8%A6%81.md#%E6%9C%AC%E6%95%99%E6%9D%90%E3%81%AE%E5%AF%BE%E5%BF%9C%E3%83%90%E3%83%BC%E3%82%B8%E3%83%A7%E3%83%B3)
- [ ] サンプルアプリの概要の説明がされている [(詳細)](https://github.com/Techpit-Market/curriculum-format/blob/master/0%E7%AB%A0%E3%81%AE%E3%83%95%E3%82%A9%E3%83%BC%E3%83%9E%E3%83%83%E3%83%88/0-1%20%E6%95%99%E6%9D%90%E3%81%AE%E6%A6%82%E8%A6%81.md#%E4%BD%9C%E6%88%90%E3%81%99%E3%82%8B%E3%82%A2%E3%83%97%E3%83%AA%E3%82%B1%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3%E3%81%AE%E3%82%A4%E3%83%A1%E3%83%BC%E3%82%B8%E3%82%92%E3%81%A4%E3%81%8B%E3%82%82%E3%81%86)
- [ ] 環境構築のカリキュラムがある [(詳細)](https://techpit-market.gitbook.io/host-guide/4/4-2#1-worinkudeshinai)

### 1章以降
- [ ] パート\(節\)のゴールを書いている [(詳細)](https://techpit-market.gitbook.io/host-guide/4/4-3#ptono-gru)
- [ ] コードや技術に関しては1つずつ丁寧に説明している [(詳細)](https://techpit-market.gitbook.io/host-guide/4/4-4#5-kdono)
- [ ] 動作確認できる箇所は画像やGIF画像を使って実装イメージを表示している [(詳細)](https://techpit-market.gitbook.io/host-guide/4/4-3#dong-zuo-que-ren)
- [ ] ファイルパスはプロジェクトルートから書いている [(詳細)](https://techpit-market.gitbook.io/host-guide/4/4-4#3-won)
- [ ] コマンドの実行結果を表示している [(詳細)](https://techpit-market.gitbook.io/host-guide/4/4-5#3-komandonowo)


## Advanced (編集者からの指摘はいたしますが、レビュー提出前に満たされている必要はありません。)
- [ ] 目標物を作成するまでの流れが書かれている [(詳細)](https://techpit-market.gitbook.io/host-guide/4/4-3#wosurumadenore-gruwosurumadenore)
- [ ] コマンドを実行する箇所と実行結果を表示する場所は分かれている [(詳細)](https://techpit-market.gitbook.io/host-guide/4/4-5#3-komandonowo)
- [ ] コードのインデントが整っている
- [ ] コード量が多い場合、前後3行を除いて必要ないコードを省略している [(詳細)](https://techpit-market.gitbook.io/host-guide/4/4-4#kdono)
- [ ] 箇条書きが続く場合は表を活用している [(詳細)](https://techpit-market.gitbook.io/host-guide/4/markdown#7-kigakuhawo)
- [ ] MVCやDockerなどの概念を説明する際はテキストだけではなく画像を使って説明している
- [ ] AWSなどの料金が発生するサービスを使用する場合、料金についての説明がある[詳細](https://techpit-market.gitbook.io/host-guide/4/4-7#awsnadogasurusbisuwosuruhasurunitsuitewosuru)
- [ ] AWSなどの料金が発生するサービスを使用する場合、リソースの削除方法についての記述がある[詳細](https://techpit-market.gitbook.io/host-guide/4/4-7#awsnadonosbisuwosuruhanonisururissugakasuru)

ご自身でカリキュラムのチェックが終わったら、Techpitの教材編集チームに連絡してください。作成された教材をレビューいたします。

レビュー後のフローは以下のようになります。

1. レビューを元に教材を修正（修正はPR上にしていただければと思います）
1. 教材を修正したことをTechpitの編集チームに連絡
1. Techpitの教材編集チームが教材をチェック
1. 1.2.3のフローを教材執筆が完了するまで繰り返す
1. 「[5章 執筆後のチェック](../5.md)」に沿って、最初からの動作確認をする
Techpitの教材編集チームがリリースに向けた準備を実施
1. リリース🎉

何か教材を作成する上で不明点や困ったことがあればお気軽にご連絡ください。
