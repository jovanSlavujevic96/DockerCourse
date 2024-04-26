# 1. go to hub.docker.com/ and search for nginx
# 2. find the "official" image -> it is called nginx
# 3. we want to use tag latest, at this point
FROM nginx:latest

# 4. Add command which we want to be executed
CMD echo "Hello world!"

# 5. build the image like this:
# $ docker build . myfirstimage:1
# "." argument will tell docker to try to find Dockerfile inside cwd
# "-t" argument will tell docker to build my image with the following tag after ":"
# "myfirstimage:1" is the name of the image + tag

# 6. run container from new image like this:
# $ docker run myfirstimage:1
# it should print "Hello world!"
