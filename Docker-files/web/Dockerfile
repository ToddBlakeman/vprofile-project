FROM nginx
LABEL "Project"="vprofile"
LABEL "Author"="ToddBlakeman"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/vproapp.conf
