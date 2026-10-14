# Nobodycam models

iPhone アプリ [Nobodycam](https://www.ultrawarp.jp/) が「残った場所だけ AI で埋める」を初めて使うときにダウンロードするモデルを置いています。

## LaMa（画像補完）— リリース `lama-v1`

[LaMa](https://github.com/advimman/lama)（Copyright 2021 Samsung Research、Apache License 2.0）を
[Core ML に変換したもの](https://huggingface.co/mlboydaisuke/LaMa-CoreML)（Apache License 2.0）を、変更せずに置いています。
`LaMa.mlpackage` の中のファイルを、そのまま 3 つに分けて添付しています。

| ファイル | mlpackage の中の場所 | SHA-256 |
|---|---|---|
| Manifest.json | Manifest.json | c814fff3cedf827c044094545ef80b0280b6cb8dd0e5c0bcf69fd31921191e58 |
| model.mlmodel | Data/com.apple.CoreML/model.mlmodel | 06a100ef99e0fd16326a3a8c4a687d13f7b26f544ea906a75338932d8554f953 |
| weight.bin | Data/com.apple.CoreML/weights/weight.bin | d0541f6044a94cd4982bfdac074fc1ccfe11d8f1f590c299d6b5071b501fc184 |

ライセンスは [LICENSE](LICENSE)（Apache License 2.0）と [NOTICE](NOTICE) を見てください。
