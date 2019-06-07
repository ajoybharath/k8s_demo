FROM gcr.io/bitnami-containers/minideb-extras:jessie-r14
FROM ajoybharath/minideb-extras:jessie-r14

MAINTAINER Ajoy Bharath <ajoybharath@gmail.com>

COPY app-code/http-app /app/http-app

USER akbharat

WORKDIR /app

EXPOSE 3000

ENTRYPOINT ["/app/http-app"]
