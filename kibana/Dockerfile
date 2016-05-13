FROM kibana:latest
MAINTAINER Anoop Nair<anoopnair.it@gmail.com>

LABEL description="Create a non-SSL based kibana entrypoint"

RUN apt-get update && apt-get install -y netcat

COPY entrypoint.sh /tmp/entrypoint.sh
RUN chmod +x /tmp/entrypoint.sh

CMD ["/tmp/entrypoint.sh"]

