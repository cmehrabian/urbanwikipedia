# Urban Wikipedia
Wiki entries aggregated by popularity. Built on top of [Wiki.js](https://github.com/Requarks/wiki)

### Development
Begin by cloning and entering this repo:
```sh
$ git clone https://github.com/cmehrabian/urbanwikipedia
$ cd urbanwikipedia
```
If you will have our config.yml (containing our mongodb creds), replace the repos config.yml file and run the commands below:

```sh
$ npm install & npm install mathjax
$ npm run build
$ npm run dev
```

Otherwise, you will have to start Mongodb locally in a new tab:
```sh
$ mongod
```
Then run the above commands:

```sh
$ npm install & npm install mathjax
$ npm run build
$ npm run dev
```

Wiki.js requires [Node.js](https://nodejs.org/) v4.6+. To install the latest stable version of node:

```sh
$ sudo npm cache clean -f
$ sudo npm install -g n
$ sudo n stable
```

Looking for a better project overview of Wiki.js? Check out the [Wiki.js Dev Guide](https://docs.requarks.io/wiki/dev-guide).

Big thanks to the folks at [requarks.io](https://www.requarks.io/) and [@NGPixel](https://github.com/NGPixel)!
