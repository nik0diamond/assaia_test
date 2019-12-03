FROM alpine:latest

RUN apk add  --no-cache ffmpeg

CMD ["ffmpeg -i rtsp://wowzaec2demo.streamlock.net/vod/mp4:BigBuckBunny_115k.mov -update 1 -q:v 1 ./bunny_latest.jpg"]
