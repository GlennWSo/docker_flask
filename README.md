# build it
docker build --tag python-docker .


# run it

docker run -d -p 5000:5000 python-docker