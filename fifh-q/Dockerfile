FROM alpine:latest AS base

RUN echo "Hello" > prefix

FROM alpine:latest

COPY main.sh .
COPY --from=base prefix prefix

ENV SHELL_ARG="cat prefix"

RUN chmod +x main.sh

ENTRYPOINT ["/bin/sh", "-c"]
CMD ["/main.sh"]