FROM williamyeh/ansible:ubuntu18.04-onbuild

RUN apt-get update && \
    apt-get -y install curl git && \
    apt-get -y install nodejs npm && \
    npm install -g @sentry/cli --unsafe-perm
