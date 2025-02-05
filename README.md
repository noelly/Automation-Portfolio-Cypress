# Automation-Portfolio-Cypress


This is repository was created by Noel Ly for personal use only


# Disclaimer

This repository is for personal use only. The content and code within this repository are provided "as is," without warranty of any kind, express or implied. The author is not responsible for any consequences or damages resulting from the use of this repository. Use at your own risk.

**Note**: This repository is not intended for commercial use or redistribution. Please respect the terms of use and refrain from copying, distributing, or modifying the content for any commercial purposes.


**Cypress Version:**
v14.0.2

**Node Version:**
v23.4.0

**NPM Version:**
v11.0.0

## Set Up
- Clone git repository
- run `npm install`

## Check and update node version with NVM

- node -v
- nvm install 23.4.0
- nvm use 23.4.0
- nvm alias default 23.4.0

## Update with latest dependencies




1. RUNNING TESTS

### Run a single test




### Run a suite



### See the report generated from the last run



### Docker 

1) Build Container

Make a build of our container based on the dockerfile configuration

 - docker build -t pw-container-test . 

2) Check if the image was properly created

 - docker images

 3) Run the image

 - docker run -it pw-container-test

 4) Run a test from inside the image

- npm run spec articleCreate

5) To exit from the image

- Control + d