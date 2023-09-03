# NodeDockerized
## Prerequisites

- Docker: [https://www.docker.com/products/docker-desktop/]
  ## Usage

1. Clone this repository.
2. Build the Docker image: using command :docker build . -t user/file (fill in user and file)
   
 Run the container:
   command : docker run -p 49160:8080 -d user/file
   Your Node.js application should now be accessible at http: http://localhost:49160 replace port numbers if others were generated.
