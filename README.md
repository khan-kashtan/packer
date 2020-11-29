### To create packer image:

1. Set project ID and ssh username at variables.json.example
2. Rename variables and build packer image: 

``` bash
mv variables.json.example variables.json
packer build -var-file=variables.json ubuntu16.json
```
