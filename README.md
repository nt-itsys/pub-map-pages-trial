# pub-map-pages-trial

> [!CAUTION]
本リポジトリは、Publicのためデータアップロードにはご注意ください。<br>
public/pagesブランチの **/docsフォルダ内** のデータは、Pagesで **全世界に公開** されます。<br>
https://nt-itsys.github.io/pub-map-pages-trial/

## pagesの設定
- public/pagesブランチの/docsフォルダを公開する
 
## 公開の流れ
1. public/pagesブランチをpull
2. /docsフォルダの中にindex.htmlを作成、中身に適当なhtmlを記述し保存。
3. public/pagesブランチにindex.htmlをpush
4. GitHubで自動的にActionsが実行され、ビルドとデプロイが行われる
5. pagesサイト上でdocsフォルダ配下が公開される
6. サイトの試写が終わったら、pagesの機能で、<ins>**unpublish**</ins>する
