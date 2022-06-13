# Git-Crypt-TEST
git cryptコマンドのテストおよび手順書

以下のファイルが暗号化されているはずです。
* ルートフォルダにある*.keyという拡張子のファイル
* secretfileというファイル
* secretdirというフォルダに入っているすべてのファイル

## 複合化した上でファイルを読み込むには。
以下を参照のこと。
* [【GitBash】git-cryptをWindows/Linux環境で活用する【git-crypt】](https://qiita.com/tmiki/items/5d403025b1f5536423b4)

~~また、今回はあくまでテストであるため、`export/exportkey.key`が公開鍵ファイルになっている。~~
キーファイルはコミットすると壊れてしまう模様。どうしてもテストしたい場合はとりあえずここにファイルを置きました。
* https://mega.nz/file/C2JWFaoa#9jE8R9tsXTx-h_B2ntNrrbTrwZXMaNhxqTvId5cVpFI