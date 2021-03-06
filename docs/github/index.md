---
layout: default
title: GitHub Index
---

# GitHub

## 基本的な用語解説

詳しくは `<用語> git` でググるといくらでも解説ページが出てきます。図で解説した方が分かりやすい項目もあるので是非調べてください。

- `Git`: 「バージョン管理システム」のひとつ
- `GitHub`: Gitのシステムを使用して、ソースコード・ソフトウェアをホスティングするWebサービス
  一般的に「リモート(リポジトリ)」と呼ばれる。対して自分の端末上に作るリポジトリは「ローカル(リポジトリ)」
- `リポジトリ (repository)`: プロジェクト・ワークスペースと同義。制作物それぞれのフォルダをひとつのプロジェクトとして「リポジトリ」と呼ぶ
  例えば `MyMaid4`
- `オーガニゼーション (organization)`: 組織・グループのこと。例えば `jaoafa`
- `コミット (commit)`: ファイルの変更をGitへ記録すること
- `コンフリクト (conflict)`: 他の人・端末で更新された内容と競合してしまうこと
  他の人の更新を受け入れるか自身の更新を最新とするかを選択し、コミットすることでコンフリクトの解消ができる
- `クローン (clone)`: リモートでホストされているリポジトリをダウンロードすること。
- `プッシュ (push)`: ローカル環境でコミットした情報をGitHubにアップロードすること
- `プル (pull)`: 他の人・端末でコミットし、プッシュした情報をダウンロードし更新すること
  クローンは最初一度のみするのに対してプルは以降何度でもする
- `フェッチ (fetch)`: リモートの更新を確認する
- `フォーク (fork)`: リポジトリをコピーして自分のリポジトリを作ること
- `ブランチ (branch)`: 現行の状態から枝分かれさせて、別の作業を行える場所を作ること
  例えば新機能を作る際に新しくブランチを作ってそこで作る…などする
- `イシュー (issue)`: バグなどの問題点を開発者に伝えたり新機能の提案をする場所、またはそのシステム
- `プルリクエスト (pull request)`: 自身が加えた更新を大本のリポジトリへも反映してもらえるようお願いすること
- `マージ (merge)`: プルリクエストを受けて、更新を大本リポジトリへも反映すること

## 具体的な解説

- [issue関連(作成・コメント)](issue)
