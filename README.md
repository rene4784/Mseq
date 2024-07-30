# Mseq - FlMML Edition

Mseqは、FlMMLをベースとした音楽作成ツールです。通常よりも機能はオミットされていますが、視覚的なシーケンサーを用いてMMLを記述でき、初心者でも簡単にMMLを作成できるように設計されています。

## 特徴
- **直感的なインターフェース**: シンプルで使いやすいピアノロールUIで、簡単に操作できます。
- **中途再生**: 独自の変換フローにより、シークバー位置からの中途再生を可能にしています。
- **音色設定**: 簡易的なエンベロープ、デチューンの管理が出来ます。本来は途中で変更切り替えすることが出来ますが、Mseｑでは1トラックにつき1種類です。

## 仕様
- 画面は上からバー移動エリア、トラック俯瞰エリア、譜面編集エリア、操作ボタン、ノート・トラック設定エリアに分かれています。
- クリック、ドラッグといった操作でノートを追加・移動編集します。オクターブを移動する場合はノート設定エリアから移動します。
- 1グリッドは8分音符分の長さで、その冪だけ伸ばすことが出来ます。
- 1トラック内で音符は重複出来ません（和音出来ません）。重ねる場合、複数のトラックを作成する必要があります。
- 音色はサイン波（@0）、ノコギリ波（@1）、三角波（@2）、矩形波（@3）、ノイズ（@7）の5種類です。デフォルトでは矩形波が設定されてます。
- トラック俯瞰エリアの四角い枠をドラッグすると、ノート編集エリアの領域が移動します。
- 「FlMMLとして出力」を押すと出力されます。
- 今のところ、保存読み込み機能とかそういうのはありません。注意してください。

## クレジット
Mseqは、以下のライブラリを使用しています。
- [flmml-on-html5](https://github.com/argentum384/flmml-on-html5) / [BSD-3-Clause license](https://github.com/argentum384/flmml-on-html5/blob/master/LICENSE)

## ライセンス
Mseqのライセンスはいずれ有効なものが決定されますが、今のところ[No License](https://choosealicense.com/no-permission/)です。

一般的な著作権法で保護されます。ただし、作者は本プログラムで生じた事物の責任をおいません（免責）。
