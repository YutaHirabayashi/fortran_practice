# fortran_practice
Fortranの勉強

## 環境構築

- 以下の記事を適宜読み替えて実施：https://qiita.com/implicit_none/items/d49c9fdf51c307d22819

- Fortran break pointという拡張を入れたら、break pointの設定が可能

- 問題点
  - デバッグ時、変数の中身が見れない
  - デバッガはdefaultでlldb
  - gdbにしようとして、記事（https://qiita.com/yuzu_afro/items/988020dd65fb4f43962a）通りに証明書などの設定をするも、以下のエラー：No executable file specified.