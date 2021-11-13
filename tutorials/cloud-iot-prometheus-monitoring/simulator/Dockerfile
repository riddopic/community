FROM alpine:3.12.8
RUN apk add --no-cache ca-certificates
ADD simulator /simulator
ADD US-cities.csv /US-cities.csv
ENTRYPOINT ["/simulator"]
