FROM httpd:2.4
COPY ./my-httpd.conf /usr/local/apache2/conf/httpd.conf
ARG REPO_URL=https://github.com/oddsummer56/oddsummer56.github.io.git
RUN ["apt-get", "update"]
RUN ["apt-get", "install", "-y", "vim"]
RUN ["apt-get", "install", "-y", "git"]
#RUN ["git", "clone", "https://github.com/oddsummer56/oddsummer56.github.io.git", "/usr/local/apache2/blog"]
RUN git clone ${REPO_URL} /usr/local/apache2/blog
