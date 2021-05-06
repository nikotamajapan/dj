# dj

--mbp


参考
https://note.com/hathle/n/n7a1cb24695aa#2TO6g

コマンド
ギットリポジトリ作ってつなぐ　の設定
1081  echo "# dj" >> README.md\ngit init\ngit add README.md\ngit commit -m "first commit"\ngit branch -M main\ngit remote add origin git@github.com:nikotamajapan/dj.git\ngit push -u origin main

venv で開発環境作る
 1082  python3 -m venv myvenv
 パスを通す
 1083  source myvenv/bin/activate
 pipをアップデート
 1084  pip3 install --upgrade pip setuptools
 必要なツールをファイルに用意
 1085  pip3 install -r requirements.txt
 ジャンゴプロジェクト始まりの呪文
 1086  django-admin startproject mysite .
 マイグレートはデータベースとか？
 1087  python3 manage.py migrate
 サーバー動かすとブラウザで見れる
 1088  python3 manage.py runserver
 
 ここから別パソコンでやった
 設定変えたらメイクマイグレエーションしよう
 1128  python3 manage.py makemigrations
 クリエートスーパーユーザーしてアドミンアカウント作成
 1132  python3 manage.py createsuperuser
 設定変えた？
 1136  python3 manage.py makemigrations
 マイグレートもう一回
 1137  python3 manage.py migrate
 動いたっぽい
 1138  python3 manage.py runserver
 
 2が終わったから次は３から
