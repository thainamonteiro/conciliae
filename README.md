# Conciliae

## Getting Started

> **Note:** If you don't want to re-build the project, you may just clone this branch directly  ```https://github.com/thainamonteiro/conciliae.git```

### 1.  Git Clone

```
git clone https://github.com/thainamonteiro/conciliae.git
```
### 2. Build the project

The cloned/downloaded repository doesn't contain prebuilt version of the project and you need to build it. You need to have [NodeJs](https://nodejs.org/en/) (v8+) with npm (v3+) installed.


Install npm dependencies 
```
npm install
```

Build the project and start local web server
```
npm start
```

Open the project [http://localhost:4000](http://localhost:4000).



## Running in Docker

You can run the project in docker. To build the container, you need to install docker and docker-compose than launch the docker daemon. After launching the daemon run the following commands from the project folder:

Build the image
```
docker-compose build
```

Launch the container
```
docker-compose up
```

