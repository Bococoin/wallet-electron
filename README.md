# bococoin-builder

# Quick start
Make sure you have [Node.js](https://nodejs.org) installed, then type the following commands known to every Node developer...
```
npm install
```

# Making a release
Copy your app files to "app/files" directory
To package your app into an installer use command:
```
npm run release
```

Once the packaging process finished, the `dist` directory will contain your distributable file.

We use [electron-builder](https://github.com/electron-userland/electron-builder) to handle the packaging process. It has a lot of [customization options](https://www.electron.build/configuration/configuration), which you can declare under `"build"` key in `package.json`.
