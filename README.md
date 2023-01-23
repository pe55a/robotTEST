# robotTEST

initialize and build the docker image

go to folder where docker file is located

    docker build -t rf_docker .

It should build successfully

then execute it 

docker run -it -v <path to folder where robot tests are located>:/tmp/tests:Z rf_docker
