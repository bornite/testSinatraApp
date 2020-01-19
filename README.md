testSinatraApp - Test application
====

Overview

This application is a sample running on GCE.

  - When request an endpoint of `test`, after waiting for a certain time, generate and return random data.
  - When request an endpoint of `test2`, after loop for a certain time, generate and return random data.
  - When request an endpoint of `test3`, read and write random data to memcached on the network.

## Requirement
  - You will need a bundler.

## Usage
  - `bundle install`
  - `bash ./start.sh`

## Author
  - [bornite](https://github.com/bornite)
