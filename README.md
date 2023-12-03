# HelloDocker

build docker image test_cpp with tag 1 with Dockerfile from current dir
docker build -t test_cpp:1 .

run single iterative mode docker image test_cpp tag 1
docker run --rm -it test_cpp:1
