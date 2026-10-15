---
title: "実践的な開発"
slug: ja-jp/real-world-development
authors:
  - geektrainer
lastUpdated: 2026-09-16
---

現実的なシナリオ、完成したアプリケーション、共有バックログを使って、ソフトウェア開発ライフサイクル全体で GitHub Copilot を活用します。変更を計画し、コードを作成し、動作をテストし、プルリクエストをレビューし、エージェントで作業を管理するプロセスを繰り返し実践します。

## シナリオ

開発をテーマにしたボードゲームのクラウドファンディングを提供する架空の企業 Tailspin Toys に、新しい開発者として参加します。チームのバックログは GitHub issue として登録済みで、すぐに作業を始められます。フィルターやページネーションなどの機能開発に加え、アクセシビリティやコーディング標準などの品質改善も含まれています。

## 作業環境を選択する

GitHub Copilot は、さまざまな作業環境で利用できます。開発方法に合った環境を選択してください。各ワークショップはそれぞれのセットアップから始まり、共通の Tailspin Toys シナリオを使用します。

### [GitHub Copilot CLI][cli]

ターミナルでエージェント型アシスタントを使います。Plan モードと Autopilot モード、指示、スキル、カスタム エージェント、Playwright MCP、Agent Merge、実用的なスラッシュ コマンドを扱います。

### [GitHub Copilot app][app]

エージェント セッションを並行して実行し、セッション モードを切り替え、Canvas で共同作業し、デスクトップ アプリで GitHub issue とプルリクエストを管理します。

### [GitHub Copilot cloud agent][cloud]

GitHub issue を非同期エージェントに割り当て、その作業を案内し、進行状況を監視して、エージェントが作成したプルリクエストをレビューします。

### [Visual Studio Code][vscode]

Visual Studio Code と GitHub Codespaces で GitHub Copilot を使います。エディターを離れずに、Copilot Chat のエージェント モード、MCP サーバー、カスタム エージェントを利用します。

[cli]: cli/
[app]: app/
[cloud]: cloud/
[vscode]: vscode/
