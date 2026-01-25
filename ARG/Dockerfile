ARG version
FROM almalinux:${version:-9}
ENV course="DevOps with AWS" \
    trainer="sunil mada" \
    duration="120HRS"
#here user1 is key, someuser is default value
ARG USERNAME=sunil
ENV USERNAME=$USERNAME
RUN echo "Hello User: ${USERNAME}, image version: ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]