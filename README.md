# the-node-beginner-book

Workshops of the [node beginner book](http://www.nodebeginner.org/).

# Running the examples

## Hello World

docker run -it --rm --name hello-world -v "$PWD":/usr/src/app -w /usr/src/app node:4 node helloworld.js
