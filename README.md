[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/l2m4x3IU)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12824841&assignment_repo_type=AssignmentRepo)
# 2023年度「プロジェクト演習A」
## 課題プロジェクト(2)テンプレート

このリポジトリ（スターターキット）にすでにあるファイルは，課題プロジェクト(2)のひな型ファイルです．

### ファイルの一覧
- README.md：このファイル
- .gitignore：リポジトリに反映しない（各自の作業用などに使うための）フォルダやファイル名を記入するファイル（最初はtmpというフォルダを無視する，と言うことが書いてある）
- docs/：今回，Github Pagesはこのフォルダを対象とする想定
- docs/index.html：トップページのテンプレート
- docs/list_example.html：紹介施設の一覧形式の例示のページ（js/readJSON_list.jsに検索機能やカテゴリ表示機能をつけることで，検索結果やカテゴリ表示機能を付けることが可能）
- docs/detail_example.html：紹介施設ごとの個別詳細形式の例示のページ（呼び出す.jsファイル名以外は課題プロジェクト1と同一→要編集）
- docs/detail_review_example.html：紹介施設のページのテンプレートから作成した個別詳細形式の例示のページ(レビュー機能付き)
- docs/data.json：紹介対象の施設などのデータを記入するJSON形式のファイル（要編集）
- docs/js/フォルダ
  - docs/js/readJSON_list.js：各チームで作成したデータファイルをページに書き込むJavaScriptプログラム（一覧形式ページ用，カテゴリ内一覧ページ，検索結果ページ）
    - カテゴリ内一覧ページ用や検索結果表示用には，ファイルをコピーして別名として対応するHTMLファイルを用いるか，内部の処理（プログラム）で対処する
  - docs/js/readJSON_detail.js：各チームで作成したデータファイルをページに書き込むJavaScriptプログラム（個別詳細形式ページ用）
  - docs/js/insert_review.js：レビューの情報をページに書き込むJavaScriptプログラム
  - docs/js/form_submit.js：レビューの書き込みをサーバに送信するJavaScriptプログラム
  - docs/js/search_list.js：一覧形式のページでNavBarの欄に入力されたキーワードによる検索を行うためのJavaScriptプログラム
- docs/css/フォルダ
  - docs/css/ProA_style.css：各チームで装飾を行うCSSファイル（要編集）
  - docs/css/star-rating.css：評価（☆の数）を表示するためのCSSファイル（編集不要）
