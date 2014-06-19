# Simple "pydoc3 -p 8001" docker image.
# Run with redirecting the port (-i to keep stdin open):
#    docker run -id -p 8001:8001 dorfsmay/pydoch
#
# build with:
#    docker build --rm=true -t dorfsmay/pydoch:$(date -u +"%Y%m%d%H%M")  pydoch
#
from ubuntu:14.04
maintainer Yves Dorfsman <yves@zioup.com>
expose 8001
entrypoint ["pydoc3", "-p", "8001"]

