# AB-730 模擬問題集

[Microsoft Certified: AI Business Professional (AB-730)](https://learn.microsoft.com/credentials/certifications/ai-business-professional/) 向けです。

- **基礎知識編:** このサイトのオリジナル 150 問（中間レベル。公式模擬と用語暗記のあいだ）
- **公式模擬:** [Microsoft Learn の Practice Assessment](https://learn.microsoft.com/ja-jp/credentials/certifications/ai-business-professional/practice/assessment?assessment-type=practice&assessmentId=650120434&practice-assessment-type=certification)（ログインして別サイトで受験）

公式模擬の問題は著作権のため、このリポジトリには入れていません。

## ブラウザで開く（こちらが本番の画面）

**https://youka419.github.io/ab-730-practice/**

`github.com` のリポジトリページはソースコードです。`index.html` をクリックしても GitHub 上では 404 やコード表示になり、クイズは動きません。

## 使い方

- **Web:** 上の GitHub Pages の URL を開く
- **ローカル:** `index.html` をブラウザで開く（同じフォルダの `questions.js` と `questions-extra.js` が必要です）

アプリ右上の **ヘルプ** に手順があります。ホームでは公式模擬と基礎知識編が別ボタンです。

## 含まれるもの

| ファイル | 内容 |
|---|---|
| `index.html` | 出題・採点・履歴・ヘルプ・公式模擬への入口 |
| `questions.js` / `questions-extra.js` | 基礎知識編 150 問（3 領域 × 50 問。中間レベル。公式 Study Guide 2026年7月22日時点） |

出題順と選択肢は毎回シャッフルされます。正解率・誤答リストは、開いているブラウザの localStorage に保存されます（GitHub には同期されません）。公式模擬の成績は Microsoft Learn 側です。

合格ライン 700 / 1000 は基礎知識編の簡易換算（正答率 × 1000）です。
