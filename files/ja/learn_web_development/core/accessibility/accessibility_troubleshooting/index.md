---
title: "評価: アクセシビリティのトラブルシューティング"
short-title: "評価: アクセシビリティのデバッグ"
slug: Learn_web_development/Core/Accessibility/Accessibility_troubleshooting
l10n:
  sourceCommit: 48d220a8cffdfd5f088f8ca89724a9a92e34d8c0
---

{{PreviousMenuNext("Learn_web_development/Core/Accessibility/Mobile","Learn_web_development/Core/Design_for_developers", "Learn_web_development/Core/Accessibility")}}

このモジュールの評価では、あなたが診断、修正するべきいくつかのアクセシビリティの問題を持った簡単なサイトを表示します。

## 出発点

評価を始めるために、[例を含むファイルの ZIP](https://raw.githubusercontent.com/mdn/learning-area/main/accessibility/assessment-start/assessment-files.zip) を取得してください。コンピューターのいずれかのディレクトリーにそのコンテンツを展開してください。

それ以外に、[CodePen](https://codepen.io/)、[JSFiddle](https://jsfiddle.net/)、[Glitch](https://glitch.com/)などのオンラインエディターを使用することもできます。

展開が完了した評価サイトは次のように見えるはずです。

![完了した評価サイトのスクリーンショット。検索入力にはプレースホルダーテキストと送信するボタンがありますが、ラベル付けはされていません。](assessment-site-finished.png)

この評価の開始時点であなたがサイトを表示したとき、いくつかの違いや問題を見つけることでしょう。これは主にマークアップ中の違いが原因であり、CSS が正しく適用されずにスタイリングの問題を引き起こしています。心配しないでください。以降の節でそれらの問題を修正します！

> [!NOTE]
> 行き詰まった場合は、[コミュニケーションチャンネル](/ja/docs/MDN/Community/Communication_channels)のいずれかに連絡してください。

## プロジェクトの概要

このプロジェクトでは、熊の「事実」に関する記事を表示する架空の自然のサイトが表示されます。現状では、これはいくつものアクセシビリティの問題を持っています。あなたの仕事は現状のサイトを見て、全力を尽くして修正し、以下の質問に答えることです。

### 色

テキストは現在のカラースキームのせいで読みづらくなっています。現状のカラーコントラスト (テキスト/背景) をテストして、テストの結果を報告し、割り当てられた色を変更して修正できますか？

### HTML の意味づけ

1. コンテンツはまだあまりアクセシブルではありません。スクリーンリーダーを使ってナビゲートしようとしたとき、何が起こるか報告してください。
2. スクリーンリーダーのユーザーがナビゲートしやすいように、記事のテキストを変更できますか？
3. サイトのナビゲーションメニュー (`<div class="nav"></div>` で囲まれた部分) は正しい HTML 意味づけ要素の中に入れることでよりアクセシブルになったかもしれません。どれを変更する必要がありますか？変更してください。

> [!NOTE]
> タグをスタイル付けする CSS ルールセレクターは、意味づけされた見出しのために適切に変更する必要があります。段落要素を加えると、スタイルもより良く見えることに気がつくでしょう。

### 画像

現状の画像はスクリーンリーダーのユーザーにとってアクセシブルではありません。修正できますか？

### 音声プレイヤー

1. `<audio>` プレイヤーは聴覚障害者にとってアクセシブルではありません。それらのユーザーのために何らかのアクセシブルな代替手段を加えることができますか？
2. `<audio>` プレイヤーは、HTML で音声に対応していない古いブラウザーを使用しているユーザーにとってアクセシブルではありません。彼らに対してどのように音声にアクセスさせることができますか？

### フォーム

1. トップにある検索フォームの `<input>` 要素はラベルとともに使用できるかもしれませんが、表示されるテキストを追加するとデザインを悪化させる可能性がありますし、視覚に問題のないユーザーにとってはあまり必要ありません。スクリーンリーダーにのみアクセシブルなラベルをどうやって追加すればいいでしょう？
2. コメントフォームの中の 2 つの `<input>` 要素は表示されるテキストラベルを含んでいますが、それらのラベルと明確に関連付けられていません。どのように関連付けますか？いくつかの CSS ルールも修正しなければいけない点に注意してください。

### コメント show/hide 制御

現状のコメント show/hide 制御ボタンは、キーボードからアクセスすることができません。タブキーによるフォーカス、リターンキーによる有効化という形で、キーボードをアクセシブルにすることができますか？

### テーブル

現状のデータテーブルはあまりアクセシブルではありません。スクリーンリーダーのユーザーにとって行と列を関連付けることは難しく、またテーブルが何を示しているのかを明確にする概要もありません。この問題を解決するために何らかの機能を HTML に追加することはできますか？

### 他には？

このウェブサイトをよりアクセシブルにする 2 つ以上の改善アイデアを挙げることができますか？

{{PreviousMenuNext("Learn_web_development/Core/Accessibility/Mobile","Learn_web_development/Core/Design_for_developers", "Learn_web_development/Core/Accessibility")}}
