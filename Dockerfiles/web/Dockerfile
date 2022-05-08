FROM nginx
LABEL "Project"="BLB"
LABEL "Author"="BE-LIKE-BRO"

RUN rm-rf /etc/nginx/conf.d/default.conf
COPY ./BLB.conf /etc/nginx/conf.d/default.conf