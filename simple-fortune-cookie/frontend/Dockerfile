FROM golang
WORKDIR /wrkdir
COPY . ./
RUN go mod download && go build -o /frontend
ENTRYPOINT ["/frontend"]