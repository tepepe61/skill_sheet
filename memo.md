# 職務経歴書のpdf生成
### github上で作成してる職務経歴書があるRepositoryをclone
git clone https://github.com/hogehoge/hogehoge.git

### npm経由でDL
npm install -g md-to-pdf

### 変換したいmarkdownファイルを指定して実行
npx md-to-pdf 職務経歴書.md
