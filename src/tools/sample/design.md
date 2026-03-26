## Overview
文字列を入力すると、Helloを付けて加工した値が出力される。
~~こんな泥臭いツールはAIに食わせて作らせてしまえ！~~
AIと協力してツールを生成するためのプロンプトのサンプルとして使用する。

## Input
ツールの入力インターフェースを記述する。

| key  | label| type | reqired | default |
| ---- | ---- | --- | --- | ---| 
| name | 名前 | str | *   |   |


## Output
/*何故かAIは思った通り（what I mean）ではなく、言った通りにしか動いてくれない石頭なので*/ 求める過程や結果と異なる場合は、挙動も記述する。

- 実行結果: str
  - `"Hello, ${name}"`


## Specs/Designs (opt)
「Output」に書きたくない細かすぎる仕様やエラーハンドルなど


## Data (opt)
ストレージ/IndexedDB、オンメモリで明示的に管理する情報。

- データ
          | 識別子
          | 保存先: 

## Interface (opt)
データの型、API、urlパラメータなどのI/F

