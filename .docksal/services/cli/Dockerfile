# Use a stock Docksal image as the base
FROM docksal/cli:2.1-php7.1

# Install hugo 0.58.3
RUN wget -q https://github.com/gohugoio/hugo/releases/download/v0.58.3/hugo_0.58.3_Linux-64bit.deb -O /tmp/hugo.deb \
    && dpkg -i /tmp/hugo.deb
