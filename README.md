## Docker Node, Bower, Grunt and PhantomJS


This repository contains **Dockerfile** of Node, Bower, Grunt and PhantomJS for [Docker](https://www.docker.io/)'s [trusted build](https://index.docker.io/u/dynaum/node-bower-grunt-phantomjs/) published to the public [Docker Registry](https://index.docker.io/).


### Installation

1. Install [Docker](https://www.docker.io/).

2. Download [trusted build](https://index.docker.io/u/dynaum/node-bower-grunt-phantomjs/) from public [Docker Registry](https://index.docker.io/): `docker pull dynaum/node-bower-grunt-phantomjs`

   (alternatively, you can build an image from Dockerfile: `docker build -t="dynaum/node-bower-grunt-phantomjs" github.com/dynaum/node-bower-grunt-phantomjs`)


### Usage

    docker run -it --rm dynaum/node-bower-grunt-phantomjs
