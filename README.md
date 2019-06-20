# docker-ts-dev-env

<!-- @import "[TOC]" {cmd="toc" depthFrom=2 depthTo=6 orderedList=false} -->
<!-- code_chunk_output -->

* [use base container](#use-base-container)
* [Usage](#usage)
	* [run container](#run-container)
* [Use Dockerhub image](#use-dockerhub-image)

<!-- /code_chunk_output -->


## use base container
- node

## Usage

### run container

```
docker run --rm -v $PWD:/root docker-ts-dev-env:<version> <commond>
```

## Use Dockerhub image

```
docker pull blackellis/docker-ts-dev-env:<version>
docker run --rm -v $PWD:/root blackellis/docker-ts-dev-env:<version> <commond>
```
