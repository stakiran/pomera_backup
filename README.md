# ポメラ DM200 用バックアップバッチ

<!-- toc -->
- [ポメラ DM200 用バックアップバッチ](#ポメラ-dm200-用バックアップバッチ)
  - [これは何？](#これは何)
    - [Q: データは Sync で同期すればよくない？](#q-データは-sync-で同期すればよくない)
    - [Q: なんで GitHub にバックアップするの？](#q-なんで-github-にバックアップするの)
  - [前提](#前提)
  - [使い方: 準備](#使い方-準備)
  - [使い方: バックアップ](#使い方-バックアップ)
  - [License](#license)
  - [Author](#author)

## これは何？
PC リンクしたポメラ DM200 のデータを GitHub にコピーするバッチファイルです。

### Q: データは Sync で同期すればよくない？
私は gmail がどうとか無線がどうとか細々しいのが嫌いなので、データバックアップは PC リンクを使うと決めています。

### Q: なんで GitHub にバックアップするの？
バージョン管理できるからです。

## 前提
バッチファイルですので Windows 用です。

## 使い方: 準備
- GitHub アカウントを作ります
- ポメラのデータをバックアップする用のリポジトリをつくります
  - 他人に見られたくないから有料プランを購入し、リポジトリを Private にしましょう
- そのリポジトリを clone した後、 `pomera_backup.bat.sample` を置いてください
- 置いた sample ファイルを `pomera_backup.bat` にリネーム後、以下を編集してください
  - `set pomera_root=g:\` の `g:\` 部分を **PCリンクされた時に認識されるドライブ名** にします

## 使い方: バックアップ
- ポメラのPCリンクでPC側に認識させます
- `pomera_backup.bat` を実行します

## License
[MIT License](LICENSE)

## Author
[stakiran](https://github.com/stakiran)
