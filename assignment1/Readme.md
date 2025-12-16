cd assignment1/files
#TO reach the required folder
docker build yourname-site .
#creating the image
docker run -d --name ycont -p 7070:80 yourname-site
#creating container and storing it in port 7070
curl http://localhost:7070
#checking 
docker stop ycont
docker rm ycont
#stopping and deleting the container
