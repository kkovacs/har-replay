har-replay
==========

A small, basic tool to replay requests from a HTTP Archive (HAR) file for testing purposes.

Installation
============

	git clone https://github.com/kkovacs/har-replay
	npm update
	node main.js <filename.har>

Usage
=====

	Usage: main.js [options]

	Options:

	-h, --help         output usage information
	-s, --site <site>  only fire requests that are for this domain (ignore everything else)
	-f, --file <file>  HAR file to replay

