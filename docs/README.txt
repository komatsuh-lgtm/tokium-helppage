このフォルダには、スタッフヘルプページで公開するPDFなどのファイルを置きます。

■ 置き方
・PDFをこのフォルダ（docs/）にコピーする
・ファイル名は半角英数字にする（日本語や空白は避ける。ハイフンやアンダースコアはOK）
  例: digisheet_manual.pdf / work_rules.pdf

■ ページに反映する方法
・content.json の該当キーに「docs/ファイル名」を書く
  例:
    "digisheet_manual_url": "docs/digisheet_manual.pdf"
    "work_rules_url": "docs/work_rules.pdf"
・空欄（""）のままだと、ページ上は「準備中」と表示されます。

■ 公開場所
・このフォルダごとGitHubリポジトリにアップロードすると、
  Cloudflare Pages 上で https://（サイト）/docs/ファイル名 として社外スタッフも開けます。
