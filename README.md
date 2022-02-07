# Scrum

## スクラムとは
アジャイル開発手法の１つ

## アジャイル開発手法とは
「事前に全てを予測することはできない」という前提で開発する

- 従来の開発手法（ウォーターフォールモデル)  
  全ての要求、工期、人的リソース、予算の全てを決めてから開発を始める
- アジャイル開発手法
  工期、人数を決める。そこで実現可能な範囲で実現可能な順から作っていく

## スクラムの目指すところ
自己組織化されたチームを作ること

## 自己組織化されたチームとは
与えられた境界内で日々のタスクをどのように処理するか決めることができる存在。  
換言すると、  
- 誰がどのタスクに取り組むか
- チームメンバーがどう助け合うか
- 新しいことを学ぶ必要があるのはいつか
- 1日の作業の優先順位をどうつけるか

を、外部の権威にとらわれず、チームが決められる状態にあること。

#### 与えられた境界内

自己組織化の範囲は以下の限定される
- スプリントゴールの決定
- バックログの作成
- プロダクトのデリバリー

## スクラムのルール

  #### スクラムの５つのイベント
    - スプリント
    - スプリントプランニング
    - デイリースクラム
    - スプリントレビュー
    - スプリントレトロスペクティブ

  #### ３つの成果物
    - プロダクトバックログ
    - スプリントバックログ
    - インクリメント
  
  #### ３つのロール
    - プロダクトオーナー
    - スクラムマスター
    - 開発者

## スクラムの５つのイベント

### スプリント
1週間～1か月の決まった期間。スクラムではこれを何度も繰り返す。  
スプリントでは  
- スプリントのゴールを達成を危険にさらすような変更はしない
- 品質を低下させない
- プロダクトバックログを必要に応じて見直す
- 必要に応じてPOと交渉する

### スプリントプランニング
スプリントにおける以下の３点を決める
  1. Why このスプリントはなぜ価値があるのか？  
  　これはスプリントゴールに対応する
  2. What 何を作るのか  
  　これはスプリント内で行うプロダクトバックログアイテムに対応する
  3. How どのように作るのか  
  　これはプロダクトバックログを詳細化したタスクに対応する

#### Why このスプリントはなぜ価値があるのか？
プランニングの最初に、POが今回のスプリントで達成したい目的を明らかにする  
プランニングの最後に、What と How で検討した内容も踏まえてスプリントの目標を簡潔にまとめる  
まとめた内容がスプリントゴールになる

#### What 何を作るのか
今回のスプリントで目的（Why）を達成するために必要なプロダクトバックログ項目を選ぶ  
　一般的に、上に並んだ項目から選んでいく  
　選ぶ個数は過去の実績をもとにする 

#### How どのように作るのか
選択したプロダクトバックログ項目を実現するための計画を立てる  
　プロダクトバックログ項目の実現するための作業を一覧化する（これがスプリントバックログになる）  
　スプリント期間中に作業を追加したり削除したりできる  
　個々の作業は１日以内で終わるように分割することが望ましい  
スプリントバックログの項目を誰が担当するかは開発者間で話し合って決める  
各項目の担当者をスプリントプランニングの段階で決めることはしない  
　開発者が作業可能な段階でスプリントバックログから必要な項目をアサインする  
 
### デイリースクラム
以下の３つの問いに答える
  - スプリントゴール達成のために昨日やったことは何か？
  - スプリントゴール達成のために今日やることは何か？
  - スプリントゴールを達成する上で障害となるものはあるか？

注）デイリーは問題解決の場ではない  
　　問題解決は必要な関係者を集めて別途時間をとって議論する

### スプリントレビュー
PO主催で行う、スプリントの成果をレビューする会  
POはステークホルダーを招待する  

最大の目的は、プロダクトに対するフィードバックを得ること  

インクリメントを実際に披露する  
プレゼン等ではなく、実際に動くところを見せる  

完成したものだけを見せる  
　なので、POと開発チームとで完成したPBIと未完成のPBIを事前に明らかにしておく  

その他、以下のことについて議論する  
- 完成しなかったPBIに対する説明
- スプリントでうまくいかなかったこと、直面した問題点、解決した方法
- プロダクトの状況とそれを取り巻くビジネス環境（POから説明する）
- PBに追加するべき項目の有無
- プロダクトを開発する上で問題となりうる事項
- 現在の進捗を踏まえたプロダクトのリリース日、完了日の予測

## スプリントレトロスペクティブ
以下について議論する  
- うまく仕事を進めるために改善できることがないか
- バグを直すのではなく、バグが生まれるプロセスを直す
- 人、関係、プロセス、ツールの観点から今回のスプリントを検査  

上記を踏まえて今後のアクションプランを作る  
作成したアクションプランのうち１つは必ず次のスプリントで実行に移す  
注）一度にたくさんのことを変更しようとしない  

## ３つの成果物

### プロダクトバックログ
- 実現したいことをリストにして並べる（注：優先度ではない）  
- 常にメンテナンスして最新に保つ
  * 項目が追加されたり削除されたりする
  * 順番は定期的に見直す
- 上位の項目は見積を済ませておく
  * 定期的に見積もりなおす

### スプリントバックログ
- 選択したプロダクトバックログ項目と実行計画
- プロダクトバックログ項目を具体的な作業に分割する
- 後から増えたり減ったりする
- 1タスクは1日以内に終わるサイズにする

### インクリメント
過去のスプリントでの成果＋今スプリントで完成したプロダクトバックログ項目  
動作して検査可能である必要がある  
事前に定めた完成の定義を満たしている必要がある

#### 完成の定義
品質基準と言い換えることもできる  
POと開発チームで事前に合意しておく  
以下は完成の定義の例
  - MR のレビュー通過
  - ユニットテスト合格
  - デプロイ完了　等々

## ３つのロール

### プロダクトオーナー
プロダクトに1人必要。
- プランニングにおける What を担当する
- プロダクトの価値を最大化するように努める
- プロダクトの責任者で、プロダクトに必ず1人必要
- プロダクトバックログの並びの最終権限を持つ
- プロダクトバックログが完成しているかを確認
- 開発チームに相談できるが干渉はしない
- ステークホルダーとの調整を担う

### スクラムマスター
チームに1人必要。
- スクラムの仕組みがうまく回るようにする
- スクラムを進める上での妨害を排除する
- スクラムチームメンバーへの支援、奉仕、教育  

注）マネージャーではないのでタスクのアサインや進捗管理はしない

やることの例
- アジャイル開発やスクラムについての説明
- スクラムイベントの会議進行
- プロダクトオーナーと開発者間の会話の促進

### 開発者
３～９人で構成される。
- プロダクトの How を担当
- モノを作る
- 全員揃えばプロダクトを作る能力が揃う
- 肩書やサブチームは無し
