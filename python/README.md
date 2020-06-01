# 1.ディレクトリ移動
```
cd 任意のディレクトリ/docker-workspace/python
```
<br><br>
# 2.Docker起動
```
docker-compose up -d
```
<br><br>
# 2.Dockerプロセス確認
```
docker-compose ps
```
StatusがUpとなっていること
<br><br>
# 3,コンテナに接続
```
docker-compose exec python bash
```
<br><br>
# 4.python起動
```
python main/main.py
```
Hello Wroldが表示される
<br><br>
# 5.プラグインインストール
```
python -m pip install tweepy
python -m pip install python-dotenv
```
<br><br>
# 6.プラグインの確認
```
python -m pip list
```
<br><br>
