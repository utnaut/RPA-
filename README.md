## RPAChallenge

### 概要
RPAチャレンジとはExcelやウェブブラウザの自動操作・自動入力練習のために
UiPathが提供しているサイト。

http://www.rpachallenge.com/?lang=JA

Excelファイルに保存されている顧客データを一件ずつ取り出し、Webフォームに登録するというシナリオ。
最後にワークフロー実行の正解率と処理速度が表示される。
通常のアプローチと高速化したアプローチそれぞれ実装。

### 高速化の工夫
- 実行前の待機時間(Delay After)、実行後の待機時間(Delay Before)の調整
- シミュレートを活用
- 並列の利用

参考：
https://www.uipath.com/ja/blog/developer/accelerate-processing
