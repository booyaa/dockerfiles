FROM debian:stretch
MAINTAINER booyaa <booyaa@booyaa.org>
RUN apt-get update && apt-get install -y curl && apt-get clean && rm -rf /var/lib/apt/lists
CMD ["curl"]
