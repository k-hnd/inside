##Execution##

### Run locally ###
* For OS X:

    ```
    brew install nodejs
    node /path/to/inside/bin/www
    ```

* For Ubuntu/Debian: 

    ```
    sudo apt-get update
    sudo apt-get install nodejs
    nodejs /path/to/inside/bin/www
    ```

Then open your browser and visit [localhost:3000](http://localhost:3000).

### Run with [WebStorm](https://www.jetbrains.com/webstorm/) ###
1. `git clone` this project.
2. Open WebStorm and click `open`, then choose `/path/to/inside/`.
3. Find `inside/bin/www` from the [`Project Window`](https://www.jetbrains.com/idea/help/project-tool-window.html).
4. Right click on the file `www` and choose `run 'www'`.
5. Then open your browser and visit [localhost:3000](http://localhost:3000).

##Database##
Let's play with [MongoDB](https://docs.mongodb.org/manual/?_ga=1.186268077.561571883.1445584874).
1. Installation
    * For OS X:

    ```
    brew install mongodb
    mongod --dbpath /path/to/inside/dev_data/mongodb/database
    ```
    Then open another terminal, run `mongo` to run MongoDB's commandline shell.
