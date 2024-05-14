FROM almalinux:8
ARG username
RUN adduser $username 
USER $username
ARG course
ARG TRAINER
RUN echo "course: ${course}, TRAINER: ${TRAINER}"
ENV course=${course}
ENV TRAINER=${TRAINER}
CMD ["sleep","100"]