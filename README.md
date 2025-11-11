## TODO管理アプリ

### 要求

* TODOを登録できる

* TODOの状態を変更できる

* TODOを削除できる

### データ

#### TODOリソース

| 名前  | 概要         | データ         |
|-------|--------------|----------------|
| ID    | 識別子       | uid            |
| NAME  | TODOの内容   | text           |
| STATE | 状態        | "todo", "done" |

### バックエンド

#### ToDoService

* GetToDo

    ToDoを取得する

* CreateToDo

    ToDoを登録する

* DeleteToDo

    ToDoを削除する

* UpdateToDo

    ToDoの情報を更新する


### フロントエンド