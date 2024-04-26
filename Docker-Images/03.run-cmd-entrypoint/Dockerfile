FROM alpine

# alpine has apk package system
RUN apk add python3

# argument to entrypoint -> we are going to ping google.com
CMD ["google.com"]

# do ping 5 times
ENTRYPOINT [ "ping", "-c", "5" ]

# to build: $ docker build . -t myweb:3
# to run:   $ docker run myweb:3
# in this case it is going to ping google.com
# if we run with extra argument, i.e.: $ docker run myweb:3 bbc.co.uk
# it is going to ping bbc.co.uk instead of google.com
# basically, it will override the CMD
