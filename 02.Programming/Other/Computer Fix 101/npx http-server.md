 What is it
`http-server` is a simple, zero-configuration command-line HTTP server that is primarily used for sharing files over a local network. It offers better performance compared to Python's `http-server`, particularly in terms of video streaming.

# Installation

`npx http-server` to use without installing

You can install `http-server` in two ways:
- Globally: Use the command `npm install --global http-server`. This allows you to use `http-server` from any location on your system.
- As a dependency in an npm package: Use the command `npm install http-server`. This installs `http-server` in the context of a specific project.

# Usage
To use `http-server`, type `http-server [path] [options]` in your command line. If a path is not specified, it defaults to `./public` if the folder exists, and `./` otherwise.

# Additional Information
For more details, visit the official npm page for `http-server` [here](https://www.npmjs.com/package/http-server).