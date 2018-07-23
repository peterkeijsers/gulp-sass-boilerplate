# gulp-sass scss compiler demo

## Introduction

This repository contains a simple example for compiling scss to css using the node (npm) modules: gulp and gulp-sass

## Installation

**Windows or Mac**

1. Download Node.js for mac or windows here: https://nodejs.org/en/download

2. Download git bash for mac or windows here: https://git-scm.com/downloads

3. Create a project directory somewhere on your local machine, for example:

    ```
    C:/Users/Experius/Desktop/projectfolder
    ```
    
4. Open the project directory using git bash or a terminal and clone the demo repository in it using the following command:

    ```
    git clone https://experius@bitbucket.org/experius/gulp-sass-demo.git
    ```
    
5. Download the repository to your local machine using the git clone command: (Change 'USERNAME' to your own bitbucket username)

    ```
    git clone https://USERNAME@bitbucket.org/experius/gulp-sass-demo.git
    ```
    
6. Install all node modules:

    ```
    npm install 
    ```
    
7. One extra NPM module is needed to run the gulp task from the command line. It 'gulp-cli'. Install it globally using:

    ```
    npm install --global gulp-cli
    ```
    
8. Then run one of the gulp tasks to start compiling scss to css:

    ```
    gulp watch
    ```
    
    or 
    
    ```
    gulp sass
    ```
    