FROM python:3-alpine
RUN apk add --no-cache ffmpeg
ARG VERSION=2024.04.09
RUN pip install --no-cache-dir yt-dlp${VERSION+==$VERSION}
ENTRYPOINT ["yt-dlp"]
# force-update 2024.04.09
