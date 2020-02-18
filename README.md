# BitID

## Before you start

As we use git submodule, you will need to clone it recursively or run the command below after cloning it.

```bash
git submodule init
git submodule update --recursive
```

## Components

The source of BitID was composed of 2 repositories.

### BitID-client

The submodule is written in web-based techniques. The front-end user interface is implemented with TypeScript, Vue.js, and Element-UI. Please refer to the README of the repo to install and run the front-end.

BitID-client allows users to customize their BitID tags and corresponding interactions via a web-app.

### BitID-server

The submodule is written in python with a light server implementation, Flask. It manages the communication with the RFID antenna, the machine learning module, and the interaction with MongoDB.

> We use MongoDB to save our data in JSON.

Please read our paper to understand how the system work, and read the README files of the two submodules for more usage.