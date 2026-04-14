# dockersitetrialone
Testing out Docker with Flask
Had nginx acting as the image earlier, then created main.py, replaced the image field with "build: ." and created main.py for Flask and Dockerfile for the custom image.


To run it, go to cmd, then cd to docker-site.

Then run docker compose --build to build the container from scratch. Also open the Docker app to see your containers.

Subsequently open the respective localhost(i've used localhost:8000 here) in your browser. Edit index.html if you hate the current test site. 
