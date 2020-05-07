# quote-gen-docker
Simple quote generator deployed in a docker container on a GCP VM

To run:
1. `docker build -t quote-gen-nginx .` to build the image.
2. `docker run --name <YOUR-CONTAINER-NAME>` -d quote-gen-nginx to run the image.
