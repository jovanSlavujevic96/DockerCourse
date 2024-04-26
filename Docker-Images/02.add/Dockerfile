FROM httpd:2.4

# add command does same thing as copy, but it also extracts compressed files
ADD ./index.tar.gz /usr/local/apache2/htdocs/

# ADD:
# 1. supports remote URLs, but you shouldn't use them, instead we should use `curl`
# 2. supports tar files where it will extract the content and copy it inside the image
