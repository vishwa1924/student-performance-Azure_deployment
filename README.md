## End to End MAchine Learning Project



## Run from terminal:
welcome

docker build -t studentperf.azurecr.io/perfcheck:latest .

docker login studentperf.azurecr.io

docker push studentperf.azurecr.io/mltest:latest
