# Sapmle projects using travis ci

- [zendesk projects](https://travis-ci.com/zendesk)
  - node_js application: [zendesk/ipcluster](https://github.com/zendesk/ipcluster)
  - ruby application: [zendesk/samson](https://github.com/zendesk/samson)
  - ruby application: [zendesk/phenix](https://github.com/zendesk/phenix)
  - java application: [zendesk/maxwell](https://github.com/zendesk/maxwell)
  - java application: [zendesk/belvedere](https://github.com/zendesk/belvedere)
- [heroku projects](https://travis-ci.com/heroku)
  - shell application: [heroku/nodejs-npm-buildpack](https://github.com/heroku/nodejs-npm-buildpack)
  - go application: [heroku/nodejs-engine-buildpack](https://github.com/heroku/nodejs-engine-buildpack)
- [openssl projects](https://travis-ci.com/openssl)
  - c application: [openssl/openssl](https://github.com/openssl/openssl)
- [openvpn projects: no public build](https://travis-ci.com/openvpn)
  - c application: [OpenVPN/openvpn](https://github.com/OpenVPN/openvpn)
  - shell application: [OpenVPN/easy-rsa](https://github.com/OpenVPN/easy-rsa)
- [yargs projects](https://travis-ci.org/yargs/yargs)
  - javascript application + windows: [yargs/yargs](https://github.com/yargs/yargs)
- [npm projects](https://travis-ci.org/npm/node-semver)
  - javascript application + windows: [npm/node-semver](https://github.com/npm/node-semver)
- [use docker in travis](https://docs.travis-ci.com/user/docker/)
  - [docker-pg-backup](https://github.com/kartoza/docker-pg-backup/blob/master/.travis.yml)
  - [logplex](https://github.com/heroku/logplex/blob/master/.travis.yml)
  - [Sending Kubernetes & Docker events to Elasticsearch and Splunk using Sysdig](https://sysdig.com/blog/kubernetes-docker-elasticsearch-splunk/)
- [How to use pastebin from shell script?](https://stackoverflow.com/questions/4013947/how-to-use-pastebin-from-shell-script)
  - pastebin needs developer key to do the post
  - curl --form 'sprunge=@yourfile.txt' sprunge.us
  - curl --form 'f:1=@yourfile.txt' ix.io
  - curl --upload-file yourfile.txt https://transfer.sh
  - cat README.md | curl -s -F "content=<-" http://dpaste.com/api/v2/


