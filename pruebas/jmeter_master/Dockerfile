# Use Ubuntu
FROM vinsdocker/jmbase

# Ports to be exposed from the container for JMeter Master
EXPOSE 60000

ADD https://github.com/emartinblas/Prueba/blob/c55b837848bf1184db0b138e155657ee3f21681d/sample_test.jmx sample_test/

ENTRYPOINT jmeter -n -t sample-test/sample-test.jmx && /bin/bash