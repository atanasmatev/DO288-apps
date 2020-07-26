FROM registry.access.redhat.com/ubi8/ubi:8.0
USER 1001
LABEL io.openshift.build.source-location="/tmp/b"
WORKDIR /
COPY meow.txt > /tmp/meow.txt
CMD bash -c "while true; do (( i++ )); echo test \$i; sleep 5; done"
