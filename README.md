# iisstart
# docker pull mcr.microsoft.com/windows/servercore/iis
# place webpage in content folder
# docker build -t iis-site .
# docker run -d -p 8000:80 --name my-running-site iis-site
# docker inspect -f "{{ .NetworkSettings.Networks.nat.IPAddress }}" my-running-site
# explorer http://172.19.245.210