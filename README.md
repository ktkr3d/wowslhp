# wowslhp

![screenshot](https://ktkr3d.github.io/images/wowslhp.png)

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/ktkr3d/wowslhp
# Go into the repository
cd wowslhp
# Install dependencies
npm install
# Run the app
npm start
```

## To Package

#### Windows
```
> yarn add electron-builder --dev
> npm run build
> npx electron-builder --win --x64 --config.nsis.oneClick=false
```

#### Linux deb
```
$ yarn add electron-builder --dev
$ npm run build
$ npx electron-builder --linux deb
```

## License

[CC0 1.0 (Public Domain)](LICENSE.md)
