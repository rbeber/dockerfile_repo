# dockerfile_repo
collection of personalized Dockerfile

### Usage example
docker build -t rbeber/ps_converter:1.06 .

docker run -it -P --name ps_utils -v C:\Users\beber:/home/work/data rbeber/ps_converter:1.06 bash 