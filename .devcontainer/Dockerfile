FROM mcr.microsoft.com/devcontainers/python:2-3.13-bookworm

COPY --from=ghcr.io/alexxit/go2rtc:latest /usr/local/bin/go2rtc /bin/go2rtc

COPY requirements.txt .
RUN python3 -m pip install --requirement requirements.txt