FROM alpine:latest

WORKDIR /first-q

COPY ./myNameAndWhatIAmLearning .

RUN chmod +x myNameAndWhatIAmLearning

CMD ["/myNameAndWhatIAmLearning"]

ENTRYPOINT ["/bin/bash", "-c"]