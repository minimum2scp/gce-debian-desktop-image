# gce-debian-desktop-image

## How to build image

### Prerequisites

* [Google Cloud SDK](https://cloud.google.com/sdk/)
* [packer](https://www.packer.io/)
* [jq](https://stedolan.github.io/jq/)

### Credentials

* https://www.packer.io/docs/builders/googlecompute.html#authentication
* https://developers.google.com/identity/protocols/application-default-credentials

### Setup `packer-vars.json`

```shell
cp packer-vars.json.example packer-vars.json
editor packer-vars.json
```

### Build image

```shell
./image.sh build
```


