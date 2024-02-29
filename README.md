WITH DOCKER 
<!--build image-->
docker  build -t pyproj2:2 .

<!--run container-->
docker run -d pyproj2:2 -p 8000:8000 --name projectp