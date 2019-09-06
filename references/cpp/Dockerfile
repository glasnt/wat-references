FROM debian:buster-slim

RUN apt-get update && apt-get install -y build-essential
COPY example.cpp .
COPY intro .

CMD ./intro && echo "\nStandard execution" && \
    gcc example.cpp -o example && ./example && \
    echo "\n\nExecuting with -trigraphs" && \
    gcc example.cpp -o example -trigraphs && ./example
