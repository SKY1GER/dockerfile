ARG version
FROM almalinux:${version:-8}
ARG ${COURSE:-DevOps}
ARG ${Trainer:-Siva}
RUN echo "${Trainer} is the trainer for ${COURSE}"
#RUN cat /etc/*release
CMD [ "cat /etc/*release" ]