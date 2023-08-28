FROM nginx
LABEL "Project"="Vprofile"
LABEL "Author"="Travis"

RUN rm -rf /etc/nginx/config.d/default.config
COPY nginvproapp.conf /etc/nginx/conf.d/vproapp.conf
