FROM golang
WORKDIR /wrkdir
COPY . ./
RUN go mod download && go build -o /backend
ENTRYPOINT ["/backend"]