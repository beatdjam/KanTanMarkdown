# かんたんMarkdown
かんたんMarkdownは完全に単一のHTMLファイルで動作するMarkdownエディタ・プレビューアです。

## かんたんマークダウン
かんたんMarkdownは**完**全に**単**一のhtmlファイルで動作するMarkdownエディタ、プレビューアです。
他のエディタに比べて、以下の特徴が売りです。

### 完全に単一のHTMLファイルで動く
名前の通り、完全に単一のHTMLファイルで動作します。したがって、JavaScriptが動作するブラウザさえあればどこでもMarkdownを利用することができます。
面倒な環境構築は不要です。

### 編集も閲覧もこれひとつ
かんたんMarkdown一つあれば編集も閲覧も一つのファイルで完結できます。面倒な変換作業は不要です。

### 画像ファイルを埋め込める
本来、HTMLファイルやMarkdownで画像を使ったページを作成する場合、文書ファイルの他に画像ファイルも配布しなければなりません。かんたんMarkdownではドラッグアンドドロップで**ファイルそのものに画像ファイルを簡単に埋め込める**ので、画像を使ったファイルも気軽に作成できます。

## すぐ使えます
次のURLからすぐに使えます。

http://tatesuke.github.io/KanTanMarkdown/

## リリースノート

### v1.20160128_02

#### 改善
* 閲覧モード時に横幅が大きすぎたので改善 

### v1.20160128_01

#### 改善
* h1がなくなった時のタイトルを[無題]にした

#### 機能追加
* info, warn, alertクラスを使うことで、青、黃色、赤枠を使えるようにした
* sequenceクラス,flowクラスを使うことでjs-sequence-diagramsとflowchart.jsを利用できるようにした


### v1.20160127_03

#### バグ修正
* スクロールバーが最下部で固定されないバグを修正

### v1.20160127_02

#### 改善
* プレビュー領域が最下部にある時は、内容更新後も最下部に固定するようにした
 + テキストエリアとプレビューのスクロールバー同期は難しそうだだったのでその代替案として
* 添付ファイルを削除する前にプロンプトを表示するようにした
* ソースコードハイライトの自動言語判定をやめ、手動指定にした

### v1.20160127_01

#### バグ修正
* 画像名を変更すると画像を表示できなくなっていたのを修正
* 画像名変更時にid属性から値を引っ張ってきているのを修正
* hrが表示されない不具合を解決

#### 機能追加、改善
* シンタックスハイライト導入
* テーブルの罫線が2重になっていたのを修正

#### 内部改善
* 画像をscriptタグに埋め込むとき、画像名はname属性に埋め込むようにした
* js内でファイルドラッグ時のスタイル適応をハードコーディングしていたのをやめた

### v1.20160126_01
* 保存のたびに</body>の前の改行が増えていくバグを修正
* MITライセンスとしました
* タブキーでタブが入力されるようにした

### v1.20160125_01
* ファイルを開いた時点では閲覧モードになるようにした
* 初期モードは閲覧モードにした
* 複数ファイル添付時の名前がおかしい問題を解決
* IEでも保存できるようにした

### v1.20160124_01
リリース
