FROM golang:1.22.1-alpine3.19 AS build
WORKDIR /app
COPY . .
RUN go build -o desafioGo


FROM scratch
WORKDIR /app
COPY --from=build /app .
ENTRYPOINT [ "./desafioGo" ]