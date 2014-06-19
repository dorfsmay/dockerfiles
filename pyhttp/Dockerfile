# Simple "python3 -m http.server" docker image for learning purposes.
# Run with redirecting the port:
#    docker run -p 8000:8000 -d
#
# build with:
#    docker build --rm=true -t "dorfsmay/pyhttp"  pyhttp
#
from ubuntu:14.04
maintainer Yves Dorfsman <yves@zioup.com>
workdir /
expose 8000
entrypoint ["python3", "-m", "http.server"]

