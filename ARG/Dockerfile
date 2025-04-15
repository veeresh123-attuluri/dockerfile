ARG version
FROM almalinux:${version:-9}
ENV course="Devops With Aws" \
    trainer="siva" \
    duration="120hrs"
ARG username=veeresh
ENV username=$username
RUN echo "Hello User: ${username}, image version : ${version}" > /tmp/Devops.txt
CMD ["sleep", "100"]