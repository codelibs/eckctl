# eckctl: ECK Control

eckctl is an utitly to manage [Elastic Cloud on Kubernetes(ECK)](https://www.elastic.co/guide/en/cloud-on-k8s/current/index.html).
eckctl creates Kubernetes cluster on [kind](https://kind.sigs.k8s.io/) as default.

## Usage

### Create ECK Cluster

```
$ ./eckctl create -k kind
```

-k option is kubernetes type. You can spcify `kind` or `eks`.

### Use Proxy

```
$ ./eckctl proxy
```

### Use CUrl

```
$ ./eckctl curl https://localhost:9200
```

### Delete ECK Cluster

```
$ ./eckctl delete -k kind
```

