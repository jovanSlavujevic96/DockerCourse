FROM httpd:2.4

# the port that container is going to listen in runtime
EXPOSE 80

# to build: $ docker build . -t myweb:4 
# to run:   $ docker run -d -P myweb:4
# "-d" stands for detach, so container keeps running in the background
# "-P" - capital letter `P`, stands for exposing the port, but it will expose the random port
# to check whether container is running: $ docker container ls
# you will get, something like this:
#############################################################################################################################
# CONTAINER ID   IMAGE     COMMAND              CREATED          STATUS          PORTS                   NAMES
# 7a2b5e2dd066   myweb:4   "httpd-foreground"   51 seconds ago   Up 50 seconds   0.0.0.0:32768->80/tcp   busy_poitras
#############################################################################################################################
# at the PORT column you can see that 32768 port has been exposed outside docker container
# and if you open the browser and enter localhost:32768 -> you should get: it works!
# afterwards, you can stop container by: $ docker container stop "7a2b5e2dd066"
