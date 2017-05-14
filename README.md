# Supported tags and respective `Dockerfile` links

-	[`7.10.0`, `latest` (*7/Dockerfile*)](https://github.com/butter/docker-node/blob/482f7fde37aa5e1d6dd3864357c8c83f1864ac6b/7/Dockerfile)
-	[`7.4.0` (*7/Dockerfile*)](https://github.com/butter/docker-node/blob/c2771744459af0be7609c4092d9e1896e5ed0d62/7/Dockerfile)
-	[`6.10.3`, `boron` (*6/Dockerfile*)](https://github.com/butter/docker-node/blob/482f7fde37aa5e1d6dd3864357c8c83f1864ac6b/6/Dockerfile)
-	[`6.9.4` (*6/Dockerfile*)](https://github.com/butter/docker-node/blob/c2771744459af0be7609c4092d9e1896e5ed0d62/6/Dockerfile)
-	[`4.8.3`, `argon` (*4/Dockerfile*)](https://github.com/butter/docker-node/blob/482f7fde37aa5e1d6dd3864357c8c83f1864ac6b/4/Dockerfile)
-	[`4.7.2` (*4/Dockerfile*)](https://github.com/butter/docker-node/blob/c2771744459af0be7609c4092d9e1896e5ed0d62/4/Dockerfile)

# What is Node?

Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine. Node.js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient. Node.js' package ecosystem, npm, is the largest ecosystem of open source libraries in the world.

> [wikipedia.org/wiki/Node.js](https://en.wikipedia.org/wiki/Node.js)

![logo](https://upload.wikimedia.org/wikipedia/commons/d/d9/Node.js_logo.svg)

# How to use this image

## Create a `Dockerfile` in your Node.js app project

```dockerfile
FROM butter/node
CMD [ "npm", "start" ]
```

or (if you need to a LTS (long term support) version):

```dockerfile
FROM butter/node:boron
CMD [ "npm", "start" ]
```

# License

View license information for [Node.js](https://github.com/nodejs/node/blob/master/LICENSE).
