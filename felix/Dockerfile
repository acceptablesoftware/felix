FROM python:3.10.0-alpine3.14

# Create and use a non-root user.
RUN adduser -D appuser
USER appuser
ENV USER=appuser
WORKDIR /home/appuser

# Do not buffer Python output and send it straight to the terminal.
ENV PYTHONUNBUFFERED=1

ENTRYPOINT /bin/sh
