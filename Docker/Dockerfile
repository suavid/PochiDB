FROM alpine:latest AS build_dependencies
RUN apk add cmake gcc g++ make

FROM build_dependencies as dev
RUN apk add git
EXPOSE 80
ENTRYPOINT ["tail", "-f", "/dev/null"]

