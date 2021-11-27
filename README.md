# Python - Jupyter notebook
docker run --rm -it -p 8888:8888 -v $PWD:/home jupyter/scipy-notebook:latest

# R - Jupyter notebook
docker run --rm -it -p 8888:8888 -v $PWD:/home jupyter/r-notebook:latest

# R
docker run --rm -it -v $PWD:/home amd64/r-base:latest

# コンテナ確認
docker ps -a

# コンテナを停止
docker stop <ID>

# コンテナを削除
docker rm <ID>