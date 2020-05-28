# SSHCode

vscode + sshをコマンドで完結させるために作成

codeコマンドを使う場合
`code --folder-uri "vscode-remote://ssh-remote+<hostname>/<path>"`

sshcodeコマンドを使う場合
```sh
sshcode foo # ホストfooのホームディレクトリにリモート接続接続
sshcode bar@foo # barユーザーとしてホストfooのホームディレクトリにリモート接続
sshcode foo:project # ホストfooのホームディレクトリにあるprojectディレクトリにリモート接続
sshcode foo:/app # ホストfooの/appにリモート接続
```