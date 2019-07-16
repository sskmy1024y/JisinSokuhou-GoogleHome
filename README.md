# 地震速報を読み上げくん

GoogleHome に、地震が来たら読み上げてもらうくん

## Require

- nodejs

## How to use

```bash
$ npm install
$ cp .env.example .env
# edit .env
$ npm start
```

## pm2 Start

```bash
$ npm i -g pm2
$ pm2 start index.js --name JishinSokuho

# watch pm2 list
$ pm2 ls

# other
$ pm2 stop     <app_name|id|'all'|json_conf>
$ pm2 restart  <app_name|id|'all'|json_conf>
$ pm2 delete   <app_name|id|'all'|json_conf>

# Generate Startup Script
$ pm2 startup
# Freeze your process list across server restart
$ pm2 save

# Remove Startup Script
$ pm2 unstartup
```

## ~~Forever Start~~

```bash
$ npm install -g forever
$ forever start index.js

# watch forever list
$ forever list

# finish forever
$ forever stop <uid in forever list>
```
