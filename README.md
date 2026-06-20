# Todo App

個人用のシンプルなTodoアプリです。

## 機能

- タスクの一覧表示
- タスクの追加
- 状態の変更（未着手 / 着手中 / 完了）
- 完了への変更
- タスクの削除
- スマホでも見やすいレスポンシブデザイン
- Supabase Databaseへの保存
- Supabase未設定時のローカル保存

## Supabase設定

1. Supabaseでプロジェクトを作成します。
2. Authentication settingsでAnonymous sign-insを有効にします。
3. SQL Editorで `supabase-schema.sql` を実行します。
4. アプリ画面のSupabase設定にProject URLとanon keyを入力します。

Project URLとanon keyはSupabaseのProject Settings > APIで確認できます。

## ローカルで使う

`index.html` をブラウザで開くだけで使えます。Supabaseを設定しない場合、タスクはブラウザの `localStorage` に保存されます。
