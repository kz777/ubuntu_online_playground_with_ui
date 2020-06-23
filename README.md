# ubuntu_online_playground_with_ui 
# Online FREE ubuntu server with ui

# open in your browser the following FREE online playground:
# https://labs.play-with-docker.com/

# pull the latest image
docker pull dorowu/ubuntu-desktop-lxde-vnc

docker images

# Run a container from the image downloaded 
docker run --name ubuntu-with-ui -p 6080:80 -p 5900:5900 d9557ce38aab

# Helpfull links:
https://stackoverflow.com/questions/40658095/how-to-open-ubuntu-gui-inside-a-docker-image


