# competition_env
簡単コンペ環境構築

## Usage
0. DockerとDocker-Composeのインストール  
`$ sudo -E sh ./INCL-SUDO-ENV.sh`
実行した後、Shellからログアウトすると`docker`コマンドが使えるようになっています

2. kaggle/pythonイメージのダウンロード
`$ docker pull kaggle/python`

3. docker containerの起動
`$ ./RUN-DOCKER-CONTAINER.sh`

4. jupyter notebookの起動
`$ nohup jupyter notebook --allow-root >> jupyter.log 2>&1 &`
