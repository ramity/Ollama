FROM ollama/ollama:latest

WORKDIR /root/.ollama
ADD docker/ollama/init.bash /tmp/init.bash

ENTRYPOINT /tmp/init.bash
