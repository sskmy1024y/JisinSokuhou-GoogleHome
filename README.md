# 地震速報を読み上げくん
GoogleHomeに、地震が来たら読み上げてもらうくん

## Require
* nodejs

## How to use
```bash
$ npm install
$ cp .env.example .env
# edit .env
$ npm start
```

## Forever
```bash
$ npm install -g forever
$ forever start index.js

# watch forever list
$ forever list 

# finish forever
$ forever stop <uid in forever list>
```
