![GitHub last commit](https://img.shields.io/github/last-commit/mattycourtney/dropbear-server)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/mattycourtney/dropbear-server)
![GitHub repo size](https://img.shields.io/github/repo-size/mattycourtney/dropbear-server)
![Code Climate maintainability](https://img.shields.io/codeclimate/maintainability/mattycourtney/dropbear-server?label=code%20quality)
![GitHub issues](https://img.shields.io/github/issues-raw/mattycourtney/dropbear-server)
![GitHub](https://img.shields.io/github/license/mattycourtney/dropbear-server)

# VMC Lunch & Learn 2020 Webinar Series - Dropbear Server

This project contains a small sinatra app used as a demo during the VMC Lunch & Learn 2020 Webinar Series. It listens on the default port 4567.

## Running with Docker

The app is dockerizied to make deploying and running it easy.

    $ docker build -t dropbear-server https://github.com/mattycourtney/dropbear-server.git
    $ docker run -d -p 80:4567 --name dropbear-server -t dropbear-server

When you've finished with the app, just stop the container.

    $ docker stop dropbear-server
