# Codefresh Go example

Original source: https://github.com/callicoder/go-docker

## Build locally

Normal docker build 

`docker build . -t go-sample-app`


## Run locally

`docker run -p 8080:8080 go-sample-app`

and then visit in your browser

* http://localhost:8080/
* http://localhost:8080/?name=John

## Build in Codefresh

Sample pipelines:

* [Simple pipeline](codefresh.yml)


Read https://codefresh.io/docs/docs/yaml-examples/examples/nomad/ for more details



