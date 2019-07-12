FROM debian:buster-slim

RUN apt-get update && apt-get install -y build-essential
COPY example.cpp .
CMD echo "\nstandard" && \
    gcc example.cpp -o example && ./example && \
    echo "\n\nwith -trigraphs" && \
    gcc example.cpp -o example_tri -trigraphs && ./example_tri
