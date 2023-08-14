This is a very simple project intented to serve as an example on how to use
docker for development with live-reload when files are changed.

See the Dockerfile and docker-compose for details on how they work.

You need docker and docker compose installed in your machine. To run it, simply
run `docker-compose up`. Updating the file `app/main.py` should trigger the
server reload and refreshing the page in the browser should get the changes
without the need of rebuilding nor reloading the container.
