# Better LINGUAPORTA
[LINGUAPORTA](https://w5.linguaporta.jp/user/seibido/index.php)の操作を超効率化(半自動化)します!

Chrome Extension for [LINGUAPORTA](https://w5.linguaporta.jp/user/seibido/index.php)

注 : 問題解答の自動化ではありません

## contents / 目次
- [feature / 機能](#feature--機能)
    - [Auto Select "単語の意味" / "単語の意味"を自動で選択する機能](#auto-select-単語の意味)
        - [設定](#disable-auto-select)で無効にできます
    - [Other / その他の機能](#others)
- [Supported Units List / サポートされているユニット一覧](#supported-units-list)
- [How to Use / インストール方法](#how-to-use)

## feature / 機能
### Auto Select "単語の意味"
問題が終わった時に、自動的に次の"単語の意味"を選択する機能

#### Disable Auto Select
"単語の意味"の自動選択を無効にする方法
1. URLバーの右側にあるアイコンのうち、`拡張機能`のアイコン(パズルの1ピース)をクリック
1. `Better LINGUAPORTA`と書かれているところをクリック
1. スライドボタンを左にして、オフにする。

### Others
- エンターキーを押すと、次のページに切り替わる。
- 正解したときのGif画像を読み込まないようにする
- **`単語の意味`**
    - 選択肢を選択したら自動的に送信される
    - 正解だったら、自動的に次の問題が表示される
- **`Study(学習書籍)`** : 学習する本を選ぶページ
    - 自動的にCOCETを選択する
        - (正確には、表示されている書籍が一つの場合、それを選択する)

## Supported Units List
- [◎] 単語の意味
- [○] 空所補充
- [△] 単語並び替え
- [×] ディクテーション

## How to Use
### 1. 拡張機能のファイル群をダウンロード
1. [ここ](https://github.com/cykps/better-linguaporta/releases)から最新の`better-linguaporta.zip`をダウンロード
2. ダウンロードしたファイルは**展開**してください

### 2. Chromeに拡張機能を読み込ませる
1. URLバーの右側にあるアイコンのうち、`拡張機能`のアイコン(パズルの1ピース)をクリック、それがない場合は`︙`をクリックしてから、`拡張機能`をクリック
1. `拡張機能を管理`をクリック
1. 開かれたページの右上の`デベロッパーモード`をオンにする
1. デベロッパーモードをオンにすると、左上に`パッケージ化されていな拡張機能を読み込む`と出てくるのでそれをクリック
1. フォルダーの選択画面が出てくるので、先ほど展開した`better-linguaporta`フォルダーを選択
1. 拡張機能が読み込まれます。やったね！(この時`エラー`と表示されるかもしれないが、Chromeのバグなので気にしなくていいです)
1. [LINGUAPORTA](https://w5.linguaporta.jp/user/seibido/index.php)を開くと、自動的に動き始めます。