FROM galexrt/vlc

USER root
RUN mkdir /home/vlc && chown vlc:vlc /home/vlc
ENV HOME=/home/vlc

VOLUME /data
ENTRYPOINT /entrypoint
COPY entrypoint /
COPY start /