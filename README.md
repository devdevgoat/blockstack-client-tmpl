# blockstack-client-tmpl
 A template app for packaging blockstack apps into a single executable using the -pkg module

## Requirements

1. Global pkg installation

2. A react app, compiled and copied to the build folder

## Setup

Install requirements:

```bash
npm install -g pkg
```

Change package.json "name" to your desired app name

## Usage

From your react app folder, run:

```bash
yarn build
```

Copy replace the build folder in this directory with the one from the last command.

Run the following within this folder:

``` bash
npm install
pkg . 
```

You can now execute the app in your desired platform without any dependancies.

## Issues

You might need to globally install micro:

```node
npm install -g micro
```
