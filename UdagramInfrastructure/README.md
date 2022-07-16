# Udagram #
AWS infrastructure for an Instagram Clone called Udagram.
This infrastructure needs to be automated so that it can be discarded as soon as the testing team finishes their tests and gathers their results.

## Deployment Instructions ##
First deploy:
```
  > ./create.sh UdagramApp udagram-infra_and_server.yml udagram-infra_and_server.json
```
Update:
```
  > ./update.sh UdagramApp udagram-infra_and_server.yml udagram-infra_and_server.json
```
Delete Stack:
```
  > ./delete.sh UdagramApp
```

## Authors

- [Mercy Resiato](https://github.com/resiato)


