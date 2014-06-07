## calciumu/illustration について

### 命名規則

``#{開始年月日}-#{タイトル}``

|説明|例|
|---|---|
|開始年月日|2014-05-26|
|タイトル|hogehoge|

### ディレクトリ構成

- illust
     - etude: 習作

### 作業方針

ラフ終了などの各時点で Pull-Request を挟み、小レビューを設けます。

### psd と GitHub

本リポジトリでは [filp/psdiff](https://github.com/filp/psdiff) を用いて pdf の diff を生成し可視化していましたが, [GitHub が psd の diff 生成に対応した](https://github.com/blog/1845-psd-viewing-diffing)ため, 利用を取りやめています.
GitHub の psd の diff 生成はまだ時間がかかり, 複数の psd の変更がある場合即座に見られませんが, 今後の進歩に期待しましょう.
