# 3DCADの埋め込みリンク
3DCADをウェブ上で表示するためのリポジトリ。  
CADソフトのeDrawingsを用いて.htmlを作成する。  
2023年度NHKロボコンで考案した機構の一部である。

# 記事への埋め込み方
1. Githubにリポジトリを作成
2. Upload existing filesを選んで生成したhtmlをアップロードしてコミット
3. Settings > Pages > Branch をmainにする
4. しばし待つ
5. https://githubのユーザー名.github.io/リポジトリ名/ファイル名.html にアクセスして表示されるか確認
表示されたら，記事に
markdown
<iframe src="https://githubのユーザー名.github.io/リポジトリ名/ファイル名.html" width=100% height=600px></iframe>
と入力すると埋め込まれる．widthとheightはお好みで．
