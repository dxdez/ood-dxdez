# The DXH Notes

This is a custom static site built using the HUGO framework. The purpose of this site is to share and save various findings related to programming. This can include bookmarks to cool sites or some random solutions to problems and challenges that have been encountered in the past. The site is in some ways a second brain for all of the extras. 

The link can be found here: [https://thedxhnotes.netlify.app/](https://thedxhnotes.netlify.app/)


### Running in Docker

The application runs within a docker container. See the official documentation for docker to set it up on your system [here](https://docs.docker.com/engine/install/ "here").

By default the server command will run with `localhost` as the url however if you are running this on a different ecosystem and would like to specify a specific url, you can do the following:
`````
server --bind {ip-address} --baseURL http://{ip-address}
`````

Execute the following command to run the application:
`````
docker compose up -d
`````

Execute the following command to shutdown:
`````
docker compose down -v
`````
