# 1. Load Docker Image
`docker load -i ollama-all.tar`
# 2. run docker Image
`docker run --gpus all -it --entrypoint /bin/bash ollama_all`

in docker console

`ollama serve`

# 3. connect docker container
`docker exec -it <container_id> /bin/bash` (get container id using `docker ps`)

in doker console

`ollama run tinyllama`
