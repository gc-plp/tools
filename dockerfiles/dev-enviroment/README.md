Docker image with virtualization based development tools and noVNC support

###### Build:
docker build -t \<container\> .

###### Run:
docker run -it --rm -p 9922:5901 -p 9923:25999 -p 9924:22 \<container\>
