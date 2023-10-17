# Deploy with Tanzu CLI
```
tanzu package install tjwa-green -p tjwa.default.tap --version 20231007210344.0.0+build.6db88c7 --service-account-name default --values-file staging/values-green.yaml -n SOME_NAMESPACE_THATS_NOT_DEFAULT
```

# Issues
- Using tanzu package install, can't deploy to default namespace, despite applying `--dangerous-allow-use-of-shared-namespace default`
    `Error: accepts 1 arg(s), received 2`