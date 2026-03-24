## Overview
文字列を入力すると、Helloを付けて加工した値が出力される。
~~こんな泥臭いツールはAIに食わせて作らせてしまえ！~~
AIと協力してツールを生成するためのプロンプトのサンプルとして使用する。

## How to use
ツールの使い方などを記述する。
/*何故かAIは意図した通り（what I mean）ではなく、言った通りにしか動いてくれない石頭なので*/ 求める挙動と異なる場合は、挙動も記述する。

- 1. ユーザー操作
  - システムの挙動（概要）
  - 1. システムの挙動（詳細）（任意）
  - 2. システムの挙動（詳細）（任意）
  - 3. `コード` `foo + bar()` `"string value"`
- 1. 文字列を入力する
  - 変化なし
- 2. 実行ボタンを押下する
  - 実行結果が表示される
  - 1. `resultIndicator` に、 `"Hello, ${入力エリア.入力欄}"` を表示する（or `resultIndicator.innerText` に、 `"Hello, ${入力エリア.入力欄}"` を設定する）


## UI structure (opt)
AIにUIの構造を指定したい場合に記載する。

- DOM要素
              | < タグや構造 >
              | 説明やID、クラス、スタイル、属性
  - DOM子要素
              | < タグや構造 >
              | 説明やID、クラス、スタイル、属性
  - DOM子要素
              | < タグや構造 >
              | 説明やID、クラス、スタイル、属性
              | innerText: `CATEGORIES.get(foo.value)`
- DOM要素
              | < タグや構造 >
              | 説明やID、クラス、スタイル、属性
- 入力エリア
              | < div >
  - 入力欄
              | < input:text >
- 出力エリア
              | < div >
  - 出力欄
              | < span >
              | id: resultIndicator



## Specs/Designs (opt)
「How to use」に書ききれないか、ユーザー操作をトリガーにしないため書きにくい仕様や設計


## Data (opt)
定数、ストレージ/IndexedDB、オンメモリで明示的に管理する情報


## Interface (opt)
「Data」で使用するデータの型、API、urlパラメータなどのI/F

