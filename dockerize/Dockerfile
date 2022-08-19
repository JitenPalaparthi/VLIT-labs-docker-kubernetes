FROM nginx:latest

LABEL author="authoor@example.com"

RUN apt update && \
   apt upgrade -y

#ADD index.html /usr/share/nginx/html

COPY index.html /usr/share/nginx/html

#CMD ["date"]

EXPOSE 80

