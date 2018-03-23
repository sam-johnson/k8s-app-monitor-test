# k8s-app-monitor-test
[![wercker status](https://app.wercker.com/status/72a4489eb1a5f2c7667b09f235a65fcc/s/master "wercker status")](https://app.wercker.com/project/byKey/72a4489eb1a5f2c7667b09f235a65fcc)

# Kubernetes application monitoring test
This is an application for kubernetes monitoring used by [kubernetes-handbook](https://github.com/rootsongjc/kubernetes-handbook)

See the API definition in [api.html](api.html).

使用方法：
docker run -d -name k8s-test -p:3000:30000 imageName

http://ip:3000/metries
