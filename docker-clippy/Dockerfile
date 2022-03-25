FROM rust:alpine

RUN apk -U upgrade
RUN rustup update
RUN apk add build-base
RUN rustup component add clippy

VOLUME [ "/src" ]
WORKDIR /src

ENTRYPOINT [ "cargo", "clippy" ]
