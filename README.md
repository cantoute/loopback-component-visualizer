# loopback-component-visualizer

[![Build status](https://travis-ci.org/yantrashala/loopback-component-visualizer.svg)](https://travis-ci.org/yantrashala/loopback-component-visualizer) [![Dep Badge](https://david-dm.org/yantrashala/loopback-component-visualizer.svg)](https://david-dm.org/yantrashala/loopback-component-visualizer.svg) [![codecov](https://codecov.io/gh/yantrashala/loopback-component-visualizer/branch/master/graph/badge.svg)](https://codecov.io/gh/yantrashala/loopback-component-visualizer) [![GitHub issues](https://img.shields.io/github/issues/yantrashala/loopback-component-visualizer.svg)](https://github.com/yantrashala/loopback-component-visualizer/issues)

### Introduction

Visualizing a model is sometimes a difficult task. When the data model gets larger, it becomes even more difficult to understand how models relate to each other.

loopback-component-visualizer helps you in creating a model diagram with a representation of all the properties, methods and relationships of your models for your loopback application.

### Table of contents
* Installation
* Usage

#### Installation

Install the module in your loopback application folder.

```sh
$ npm install loopback-component-visualizer --save
```

#### Usage

Inside your component-config.json, add the loopback-component-visualizer and a '/visualize' api will be mounted to your server.

You can browse @ http://host:port/visualize

```sh
"loopback-component-visualizer": {
  "mountPath": "/visualize"
}
```

#### Preview

![A Relational Model](https://github.com/yantrashala/loopback-component-visualizer/blob/master/preview.png?raw=true "A Relational Model")
