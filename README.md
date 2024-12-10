# C# Minimal API Demo

このプロジェクトは、C# 9のMinimal APIを使用した簡単なTODOアプリケーションのデモです。

## 機能

- ToDo項目の一覧表示
- ToDo項目の追加
- ToDo項目の更新
- ToDo項目の削除
- Swagger UIによるAPI文書化

## 技術スタック

- .NET 6.0
- Entity Framework Core (InMemory Provider)
- Swagger / OpenAPI

## セットアップ手順

1. リポジトリをクローン：
   ```bash
   git clone https://github.com/hmoriya/minimal-api-demo.git
   ```

2. プロジェクトディレクトリに移動：
   ```bash
   cd minimal-api-demo
   ```

3. アプリケーションを実行：
   ```bash
   dotnet run
   ```

4. ブラウザで以下のURLにアクセス：
   - Swagger UI: https://localhost:7001/swagger
   - API エンドポイント: https://localhost:7001

## API エンドポイント

- GET /todos - ToDo項目の一覧を取得
- GET /todos/{id} - 指定したIDのToDo項目を取得
- POST /todos - 新しいToDo項目を作成
- PUT /todos/{id} - 既存のToDo項目を更新
- DELETE /todos/{id} - ToDo項目を削除

## 開発環境

- Visual Studio 2022 または VS Code
- .NET 6.0 SDK
