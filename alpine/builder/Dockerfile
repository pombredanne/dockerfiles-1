FROM alpine:3.10
COPY mkimage-alpine.bash /
RUN apk upgrade --no-cache
RUN apk add --no-cache bash tzdata xz
ENTRYPOINT ["bash", "/mkimage-alpine.bash"]
