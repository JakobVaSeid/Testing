FROM --platform=linux/amd64 debian:bullseye-slim

# Install necessary tools
RUN apt-get update && apt-get install -y \
	build-essential \
	curl \
	git \
	pkg-config \
	&& rm -rf /var/lib/apt/lists/*

RUN echo 'export PS1="\W> "' >> ~/.bashrc