# trash

Move your files / directories to Trash box in command line.  
This tool works only on macOS.

コマンドラインからファイルやディレクトリをゴミ箱に入れられます．  
macOS 専用ツールです．

## Installation / インストール

Just [download](https://github.com/h-matsuo/macOS-trash/releases/latest) the script file and move it in `/usr/local/bin`.  
You can also try the following code in command line:

スクリプトファイルを[ダウンロード](https://github.com/h-matsuo/macOS-trash/releases/latest)し，`/usr/local/bin` に配置してください．  
次のコードをコマンドラインから実行することでもインストールできます：

```sh
$ curl -O https://raw.githubusercontent.com/h-matsuo/macOS-trash/master/trash; chmod +x trash; mv trash /usr/local/bin
```

## Usage / 使い方

### Delete / 削除

```
$ trash [-r] <file>...
```

Option "`-r`" is required when you remove directory.

ディレクトリを削除する場合，オプション "`-r`" が必要です．

### Put Back / 戻す

Currently, putting the file back from Trash box is not currently supported.  
However, you can put it back with GUI (use Finder.app).

現在，ゴミ箱からもとに戻す機能はサポートされていません．  
しかし，GUI を用いて戻すことができます（Finder.app を使用してださい）．

<!-- ![Put back](https://github.com/h-matsuo/macOS-trash/wiki/images/put_back.png) -->

<img src="https://github.com/h-matsuo/macOS-trash/wiki/images/put_back.png" width="500px" alt="Put back">

## License / ライセンス

MIT License.
