FROM alpine:latest

WORKDIR /1

COPY ./myNameAndWhatIAmLearning .

RUN chmod +x myNameAndWhatIAmLearning

CMD ["/myNameAndWhatIAmLearning"]

ENTRYPOINT ["/bin/bash", "-c"]