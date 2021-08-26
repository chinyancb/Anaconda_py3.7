# anaconda_py3.7

## image build
docker build -t \<your image name\> ./

## Docker run
docker run -it -p 8080:8888 --rm --name \<name\> --mount type=bind,src=\`pwd\`,dst=/workdir
