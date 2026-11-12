# 諏訪圏工業メッセ2026｜見学記録

個人向けの展示会見学管理ツール。2026年11月13日 14:30〜16:00の見学に使用。

## 機能
- 全337件の出展企業・団体と重点20件の閲覧
- 東西体育館の絞り込み・検索・企業概要・場所の表示
- 「訪問済」「再訪希望」「見送り」の記録と自由メモ
- JSONバックアップ・復元とCSV出力
- 静的HTML + Service Worker。公開後の初回読み込みでオフライン表示対応

## 公開
GitHub Settings > Pages > Build and deployment > Deploy from a branch > main / (root) > Save。

## 保存・プライバシー
記録はブラウザの localStorage に保存され、GitHubに送信されません。Safariとホーム画面版では保存領域が異なる場合があります。バックアップ機能で記録を保管してください。

## データの注意点
収録内容はユーザー提供のExcelを元にしており、事業内容の一部は「要確認」です。現地の出展・展示内容は公式の情報を優先してください。
公式フロアマップ: https://suwamesse.jp/wp2024/wp-content/uploads/2026/11/2026_floormap.pdf
公式出展企業一覧: https://suwamesse.jp/exhibiting-list

## デザインについて
[Taste Skill](https://github.com/Leonxlnx/taste-skill) のデザイン原則（情報階層、一貫したトークン、実用的なUI、ブラウザ検証）を参考に、業務ツールの文脈に合わせて再設計しました。作者のリポジトリやコードは変更・複製していません。

本アプリは諏訪圏工業メッセの公式アプリではありません。
