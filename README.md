# HelloDocker

build docker image test_cpp with tag 1 with Dockerfile from current dir:
docker build -t giebsy/my_first_repo:1 .

run single iterative mode docker image test_cpp tag 1:
docker run --rm -it giebsy/my_first_repo:1

docker login -u ....
docker push giebsy/my_first_repo:1

 docker compose up -d
 ./giebsy/my_first_repo:1
 docker compose down
