FROM golang:1.16.5

RUN mkdir /echo

COPY dummy.go /echo

EXPOSE 9999

CMD ["go", "run", "/echo/dummy.go"]