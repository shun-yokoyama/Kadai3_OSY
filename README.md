## 共同開発の流れ

### 1. リモートリポジトリに接続する。
    git remote add origin <url>
### 2. リモートからローカルにデータを持ってくるためにクローンで複製する。
    git clone <url>
### 3. ブランチを切る。（新しくブランチを作る。）以下の作業はこのブランチで行う。
    git checkout -b <新しいブランチ名>
### 4. OSY.cを開き、自分の名前を書き込む。
    notepad OSY.c
### 5. 変更点に対するステージングとコミットを行う。
    git add OSY.c
    git commit OSY.c -m "名前入力完了(氏名)"
### 6. 変更点を確認する。
    cat OSY.c
### 7. リモートリポジトリにpushする。
    git push origin <ブランチ名>
### 8. githubにCompare&pull requestが届く。（横山が許可を出す）
    グループLINEで教えてほちい。
### 9. 3人の名前記入が終わり次第、pullをしてローカルを最新状態にする。
    git pull origin <ブランチ名>
