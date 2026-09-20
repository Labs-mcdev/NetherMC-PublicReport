# NetherMC プレイヤー通報と処分への異議申し立て

[English](../../README.md) · [中文](README.zh.md) · **日本語** · [हिन्दी](README.hi-IN.md)

> 言語版に相違や曖昧さがある場合、NetherMC の規則は英語版を基準とします。規則の表現や翻訳に関する問題は、[Security and quality](https://github.com/SchemaFoxLabs/NetherMC/security) の **Report a vulnerability** から報告してください。

## リポジトリの用途

Staff がオフラインのときのプレイヤー通報と、誤って適用されたと思われる制限への異議申し立てに使用します。Staff がオンラインの場合はゲーム内通報を優先してください。スキンはゲーム内でのみ通報できます。

サーバー／ウェブサイトの不具合、質問、機能提案は[メインリポジトリ](https://github.com/SchemaFoxLabs/NetherMC/issues/new/choose)に提出してください。脆弱性はメインリポジトリの[非公開セキュリティ経路](https://github.com/SchemaFoxLabs/NetherMC/security)で報告してください。

## クイックナビゲーション

- **[サーバーとコミュニティの規則](https://github.com/SchemaFoxLabs/NetherMC/blob/main/docs/i18n/SERVER_RULES.ja-JP.md)**
- **[プレイヤー通報を提出](https://github.com/Labs-mcdev/NetherMC-PublicReport/issues/new?template=player_report.yml)**
- **[メディア証拠なしの通報を提出](https://github.com/Labs-mcdev/NetherMC-PublicReport/issues/new?template=player_report_no_media.yml)** — CSAM Content または Illegal PlayerID
- **[処分への異議申し立てを提出](https://github.com/Labs-mcdev/NetherMC-PublicReport/issues/new?template=appeal.yml)**
- **[メインリポジトリ](https://github.com/SchemaFoxLabs/NetherMC)**

## プレイヤー通報

プレイヤー通報には有効なゲーム内 **Report-ID** が必要です。Staff は対応するゲーム記録から通報者と対象プレイヤーを確認します。番号を知っているだけで本人確認が完了するわけではありません。

Streamer Mode はチャットの関連表示を隠します。通報記録は次のコマンドで確認できます。

```minecraft-command
/report-mylist
```

古い記録は定期的に削除されます。元の ID が利用できない場合は、事件が発生したサブサーバーで新しい ID を取得してください。

```minecraft-command
/inforeport
```

元の事件の時刻と経緯は正確に記載してください。新しい ID で削除済みの記録が復元されることはありません。

**Report-ID → 事件の背景 → 確信度と根拠 → 個人情報などを伏せた証拠**の順に整理してください。確信度が高いほど、より明確で完全な証拠が必要です。確信度は通報者の自己評価であり、処分を直接決めません。

CSAM Content または Illegal PlayerID には、メディア証拠なしのフォームを使用してください。CSAM をダウンロード、コピー、アップロード、転送したり、リンクを提出したりせず、画像を含まない特定用情報だけを提供してください。

## 処分への異議申し立て

### Join Block

制限中はメインロビーとすべてのサブサーバーに接続できません。権限を持つ `Author` が解除できます。接続画面には次を表示します。

- `block reason`
- `block-ID`

### SubServer Block

制限中は対象サブサーバーに接続できません。権限を持つ `Author`、`Staff`、`Admin` が解除できます。チャットには次を表示します。

- `block reason`
- `block-ID`
- `block-duration`

### Feature Block

制限中は Ranked、公開チャット、私信、サブサーバー間チャットなどの対象機能を利用できません。権限を持つ `Author`、`Staff`、`Admin` が解除できます。チャットには次を表示します。

- `disable reason`
- `disable-duration`

処分期間は[サーバーとコミュニティの規則](https://github.com/SchemaFoxLabs/NetherMC/blob/main/docs/i18n/SERVER_RULES.ja-JP.md)に従います。

異議申し立てには、制限の種類、任意の **Player ID**、対象サブサーバーまたは機能、おおよその時刻（**UTC−8**）、表示された理由、異議の理由、任意の編集済み補足資料を記載してください。Player ID を空欄にする場合は、公開 Issue で非公開の連絡方法（利用できれば PM）を求め、その非公開の方法だけで ID を提供してください。

## プライバシーと対応

本名、私的な連絡先、認証情報、非公開のアカウント情報、機微な識別子、無関係な個人情報を公開しないでください。スクリーンショットは判断に必要な文脈を残して編集してください。

Staff は対応可能な時間と証拠に応じて処理します。通常 **1～7 日**、繁忙期 **8～30 日**は、最初の対応または返信の目安です。

補足資料の提出前相談：`mc-contact@schemafoxlabs.com`。機微な証拠を送る前に適切な方法を確認してください。**20 MiB** を超える添付ファイルは受信できない場合があります。
