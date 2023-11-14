## Introduction

- Hugo is a [[static-site]] generator that converts markdowns to html

### Setup

for Ubuntu based distro, get the Hugo Package from apt
```bash
#Install Using apt
sudo apt install hugo;
#Serve the Site
hugo serve
```

## Create pages

- create .md files inside the **resources** folder
- create URL for the page by changing the config.yaml

## Deployment

1. cmd for compiling assets to public dir:
```bash
#Compile assets for Deployment
hugo
```
2. push public dir to [[github]] & point to index.html in the server.