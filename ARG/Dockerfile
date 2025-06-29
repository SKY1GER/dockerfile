ARG version
FROM almalinux:${version:-8}
ARG COURSE=DevOps
ARG Trainer=Siva
ARG Duration=120h0urs
ENV Duration=${Duration}
RUN echo "${Trainer} is the trainer for ${COURSE}, Duration: ${Duration}"
#RUN cat /etc/*release
CMD [ "cat /etc/*release" ]