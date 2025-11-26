ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="DOCKER" \
    TRAINER="SIVA"
ENV COURSE=${COURSE}
RUN echo "Trainer: ${TRAINER}, Course: ${COURSE}, version: ${VERSION}"
CMD ["sleep", "100"]