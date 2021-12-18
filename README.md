How to run

- `cd` into the project folder.
- Build the image: `docker build -t ibl-docker-test:1.0.0 .`
- Run the image: `docker run -p 8080:80 ibl-docker-test:1.0.0`
- Access the page: `http://localhost:8080/`

Run image publicly hosted on dockerhub
`docker run -p 8080:80 romoka/ibl-docker-test:1.0.0`
