FROM python:3.7.13-alpine3.16
COPY ./hostloc_auto_get_points.py /root/hostloc_auto_get_points.py
COPY ./supercronic /usr/local/bin/supercronic
RUN chmod +x /usr/local/bin/supercronic
COPY ./my-cron /root/my-cron
CMD ["/usr/local/bin/supercronic", "/root/my-cron"]
