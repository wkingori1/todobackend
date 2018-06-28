FROM wkingori1/todobackend-base:latest
MAINTAINER David Kingori <wkingori1@gmail.com>

# Copy application artifacts 
COPY target /wheelhouse


# Install application
RUN . /appenv/bin/activate && \
    pip install -f /wheelhouse todobackend && \
    rm -rf /wheelhouse