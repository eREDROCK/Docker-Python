FROM python:3.9

# pip(Pythonのパッケージ管理システム)のアップデート
RUN pip install --upgrade pip

# pipでインストールしたいモジュールをrequirements.txtに定義する
# コンテナ内でpipコマンドを実行してインストールさせる
COPY requirements.txt ./
RUN pip install -r requirements.txt
