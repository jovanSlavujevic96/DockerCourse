# https://hub.docker.com/_/httpd
# never use 'latest' image version in production
FROM httpd:2.4

# copy 'index.html' inside the image
COPY ./index.html /usr/local/apache2/htdocs/

# to build: $ docker image build . -t myweb:1
# to run:   $ docker container run -p 8080:80 myweb:1
# "-p" argument tells docker to expose port 8080 outside docker & 80 inside

# open broweser and type: localhost:8080
# there should be page which shows content from 'index.html'
