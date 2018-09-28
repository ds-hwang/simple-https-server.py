# How to run
* Copy `server.pem` to your preparable folder.
* Change the absolute path in `simple-https-server.py`.
* (Optional) Set the folder including `simple-https-server.py` to path env.
* Go to your local project directory for web service.
* Run
```
> simple-https-server.py
--------------------------------------------------------------------------------
Server running on https://localhost:4443
--------------------------------------------------------------------------------
10.7.200.64 - - [28/Sep/2018 14:18:18] "GET / HTTP/1.1" 200 -
10.7.200.64 - - [28/Sep/2018 14:18:18] "GET /node_modules/three/build/three.min.js HTTP/1.1" 200 -
10.7.200.64 - - [28/Sep/2018 14:18:18] "GET /node_modules/three/examples/js/loaders/MTLLoader.js HTTP/1.1" 200 -
10.7.200.64 - - [28/Sep/2018 14:18:18] "GET /node_modules/three/examples/js/loaders/OBJLoader.js HTTP/1.1" 200 -
10.7.200.64 - - [28/Sep/2018 14:18:18] "GET /node_modules/three/examples/js/controls/PointerLockControls.js HTTP/1.1" 200 -
```

# Refereces
* [Original code](https://gist.github.com/dergachev/7028596#gistcomment-1494011)