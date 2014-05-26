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

### psdiff

本プロジェクトは psdiff を用いて psd ファイルから png ファイルを commit 時に自動生成し、psd ファイルの diff を見やすくしています。

[filp/psdiff](https://github.com/filp/psdiff)
