## Gitのミニレポート
### Q3-1. Git同様のバージョン管理システムの1つにSubversionがある。Subversionの特徴および問題点を説明せよ。
* 特徴
　 中央のリポジトリサーバーを中心に管理する「集中型モデル」を採用していて、開発者はサーバーから最新版をチェックアウトし、変更をコミットすることで中央に履歴が保存される
* 問題点 
  複数の人が同じ時間に同じファイルに編集を加えると競合が発生する
### Q3-2. Subversionの問題点をGitではどのように解決しているか説明せよ。
* Subversionの問題点
　　コミットやログの確認に常にネットワークが必要
* Gitにおける解決方法
　ローカルリポジトリによりネットワーク不要でコミット、ブランチ、ログ閲覧が可能
　
### Q3-3. Gitの機能の中で、複数人でのシステム開発において、特に重要となる機能を1つ選び説明せよ。
* 複数人でのシステム開発で重要となるGitの機能
　　ブランチ機能
* その理由（具体的な状況とその機能を使った役割分担など）
　　同じリポジトリ上で、複数人が並行して作業できる
　　作業中の変更が他の人に影響せず、後からマージできる
