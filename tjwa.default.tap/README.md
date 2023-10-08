# Build
```
tanzu apps workload create tjwa \
--git-repo https://github.com/xtreme-sameer-vohra/tanzu-java-web-app \
--git-branch main \
--type server \
--label app.kubernetes.io/part-of=tjwa \
--label apps.tanzu.vmware.com/carvel-package-workflow=true \
--yes \
--namespace default
```