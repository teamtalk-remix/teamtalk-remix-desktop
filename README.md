# TeamTalk Remix Desktop

TeamTalk Remix Desktop is a cross-platform TeamTalk Remix client for GNU/Linux, macOS, and Windows.

## Build

### Build from source

TeamTalk Remix Desktop is an [Electron][] based application and uses [yarn][] to manage dependencies.

- Make sure you have [Node.js][] and [yarn][] installed.
  ```bash
  # Fedora, RHEL, CentOS
  yum install nodejs
  npm install -g yarn
  # Debian/Ubuntu
  apt install nodejs
  npm install -g yarn
  # macOS
  brew install node
  npm install -g yarn
  # Windows
  scoop install -g nodejs
  npm install -g yarn
  ```
- Install build dependencies:
  ```bash
  yarn
  ```
- Build the application:
  ```bash
  yarn build
  ```
- Start the application:
  ```bash
  yarn start
  ```

[Electron]: https://electronjs.org/
[Yarn]: https://yarnpkg.com
[Node.js]: https://nodejs.org
