# Unifi Local Setup with docker

## Setup

1. Copy files to device with: `rsync -v -r --exclude .git ./ pi@10.0.0.2:unifi/`
1. Navigate to folder: `cd ~/unifi`
1. `cp mongo.env.example mongo.env`
1. Fill in / generate envs
1. Run docker container with `docker compose up -d` in background mode

## Reset

1. Reset by removing `./data` and `./config` folder
