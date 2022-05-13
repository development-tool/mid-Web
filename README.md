# mid-Web
フロントエンド用レポジトリ

## 環境構築

* Homebrew環境

### nodeの設定（via nodebrew)
すでに設定されているかはnode -vもしくは which nodeで確認
```
// nodebrew経由でnodeをinstallするのでnodebrewそinstall
$brew install nodebrew
// nodebrewに入っているnode versionの確認
$nodebrew ls
// 上記で確認したnodeのversionを指定して使用するnode versionの設定
$nodebrew use v16.6.2
// shellがzshの場合は以下でnodeのpathを通す
$echo 'export PATH=$HOME/.nodebrew/current/bin:$PATH' >> ~/.zshrc
// terminalを再起動
$source ~/.zshrc
//nodeのpathが通っていることを確認
$ which node
```
### node moduleの設定
```
$npm install --save-dev typescript ts-loader webpack webpack-cli webpack-dev-server
$npm install -g typescript
```
