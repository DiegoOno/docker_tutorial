FROM nginx:latest
LABEL maintainer 'Diego from Seebot <diego@seebot.com.br>'

RUN echo '<h1>Without content<h1>' > /usr/share/nginx/html/content.html
COPY *.html /usr/share/nginx/html/