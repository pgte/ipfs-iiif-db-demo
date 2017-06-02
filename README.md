# ipfs-iiif-db-demo

> IPFS IIIF Demo

## Apps

### 1. Mutator

* User can add or remove a random annotation from the annotation list (using the add and remove buttons).
* Tracks changes to the annotation list and prints the latest
* Lists the connected peers

URLs:

  * local: http://localhost:54321/mutator/public/index.html
  * remote: https://pgte.github.io/ipfs-iiif-db-demo/public/mutator/public/index.html


### 2. Tracker

* Tracks changes to all annotation lists in the 'iiif' partition
* Lists the connected peers

URLs:

  * local: http://localhost:54321/tracker/public/index.html
  * remote: https://pgte.github.io/ipfs-iiif-db-demo/public/mutator/public/index.html

### 3. Auto Mutator

* Every 2 seconds, adds a random annotation from the annotation list.
* Tracks changes to the annotation list and prints the latest
* Lists the connected peers

URLs:

  * local: http://localhost:54321/auto-mutator/public/index.html
  * remote: https://pgte.github.io/ipfs-iiif-db-demo/public/auto-mutator/public/index.html


## Source code

Source code for this is in the [examples folder](https://github.com/pgte/ipfs-iiif-db/tree/master/examples) of [ipfs-iiif-db](https://github.com/pgte/ipfs-iiif-db).

# Use without installing it

If you wish to access these demo apps without installing them locally, go to:

http://pgte.github.io/ipfs-iiif-db-demo/public/

# Install

Clone using Git:

```bash
$ git clone https://github.com/pgte/ipfs-iiif-db-demo.git
```

CD into it and install dependencies:

```bash
$ cd ipfs-iiif-db-demo
$ npm install
```

# Start

```bash
$ npm start
```

Open [http://127.0.0.1:54321](http://127.0.0.1:54321).

You should now have links to all 3 apps: Tracker, Mutator and Auto-Mutator.

# License

MIT