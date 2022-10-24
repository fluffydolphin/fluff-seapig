# fluff-seapig - this is a lite weight website using html, css and javascript

## What is keylogger?
fluff-seapig website, is a website make with html, css and javascript. It can be run on docker (in my opinion docker is better because its easier to run and uses less resources) and apache2.

# How to install and run?

## Docker install

https://hub.docker.com/repository/docker/fluffydolphin/fluff-seapig

## How to install git for cloning

1. Install git
   ```sh
   sudo apt install git
   ```



## Cloning using git and run on apache2.

1. Install apache2
   ```sh
   sudo apt install apache2
   ```
2. Clone the repo
   ```sh
   git clone https://github.com/fluffydolphin/fluff-seapig.git
   ```
   3. Restart apache2
   ```sh
   sudo systemctl restart apache2
   ```
      ```sh
      localhost:80 or locahost:8080
      ```
