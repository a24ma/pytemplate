<!-- title: pytemplate -->

# [pytemplate](https://github.com/a24ma/pytemplate)

* Created on: 2024/10/16 (水) 
* Updated on: 2024/10/16 (水) 

## Introduction

Python 用のテンプレート。

主に vscode のスニペット登録用。

### py_full_template

Python Script 用のテンプレート。

* 正常終了・異常終了時の、修了後待ち受け処理付き。
    * bash を想定。
* logging を想定したログ管理。
    * 



## スニペット用

### 参考サイト

* 変換ツール: https://migi.me/vsc_snippet/

### Snippet 変数名

* `TM_SELECTED_TEXT`: 現在選択しているテキスト
* `TM_CURRENT_LINE`: 現在の行の内容
* `TM_CURRENT_WORD`: 現在のカーソル位置の単語（もしくは空白）
* `TM_LINE_INDEX`: 最初の行を０行目としたときの現在の行番号
* `TM_LINE_NUMBER`: 最初の行を１行目としたときの現在の行番号
* `TM_FILENAME`: 現在のドキュメントのファイル名
* `TM_FILENAME_BASE`: 現在のドキュメントのファイル名（拡張子なし）
* `TM_DIRECTORY`: 現在のドキュメントのディレクトリ
* `TM_FILEPATH`: 現在のドキュメントのフルのファイルパス
* `RELATIVE_FILEPATH`: 現在のドキュメントの相対（開いているワークスペースやフォルダに対する）ファイルパス
* `CLIPBOARD`: クリップボードの内容
* `WORKSPACE_NAME`: 開いているワークスペースまたはフォルダーの名前
* `WORKSPACE_FOLDER`: 開いているワークスペースまたはフォルダーのパス
* `CURRENT_YEAR`: 現在の年
* `CURRENT_YEAR_SHORT`: 現在の年の下2桁
* `CURRENT_MONTH`: 2桁の月 (例 '02')
* `CURRENT_MONTH_NAME`: 月の正式名称（例：'July')
* `CURRENT_MONTH_NAME_SHORT`: 月の略称（例：'Jul'）。
* `CURRENT_DATE`: 2桁の日付(例：'08')
* `CURRENT_DAY_NAME`: 曜日名 (例: 'Monday')
* `CURRENT_DAY_NAME_SHORT`: 曜日の略称（例：'Mon')
* `CURRENT_HOUR`: 24時間表示での現在時刻
* `CURRENT_MINUTE`: 現在の分を2桁で表示
* `CURRENT_SECOND`: 現在の秒を2桁で表示
* `CURRENT_SECONDS_UNIX`: Unixエポックからの秒数
* `RANDOM`: 10進数6桁の乱数
* `RANDOM_HEX`: 16進数6桁の乱数
* `UUID`: バージョン4のUUID
* `BLOCK_COMMENT_START`: 出力例：C++の場合 /* またはHTMLの場合 <!--
* `BLOCK_COMMENT_END`: 出力例：C++の場合 */ またはHTMLの場合 -->
* `LINE_COMMENT`: 出力例：C++の場合 //
* `1`～`9`: タブストップ$1～$9の内容
* `CURSOR_INDEX`: マルチカーソルの最初の選択を0とした番号
* `CURSOR_NUMBER`: マルチカーソルの最初の選択を1とした番号