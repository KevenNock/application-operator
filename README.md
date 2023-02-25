# application-operator

## Kubernetes Operator一书的源码，可以直接安装,修正版本

## 版本信息

#### 操作系统
ubuntu 22.10

### docker 版本
* docker Version:   20.10.16

### kind版本，以及创建集群方式
* kind version 0.12.0
```k8s
kind create cluster --config multi-node-config.yaml --image=kindest/node:v1.22.0 --name=dev
```

### kubectl版本
* kubectl version v1.22.0
```k8s
kubectl version  --short
Client Version: v1.22.0
Server Version: v1.22.0
```

## kubebuilder 版本
* kubebuilder version  3.2.0
```k8s
kubebuilder version
Version: main.version{KubeBuilderVersion:"3.2.0", KubernetesVendor:"1.22.1", GitCommit:"b7a730c84495122a14a0faff95e9e9615fffbfc5", BuildDate:"2021-10-29T18:32:16Z", GoOs:"linux", GoArch:"amd64"}
```

## kustomize 版本
* kustomize version  v4.2.0
```k8s
kustomize version
{Version:kustomize/v4.2.0 GitCommit:d53a2ad45d04b0264bcee9e19879437d851cb778 BuildDate:2021-06-30T22:49:26Z GoOs:linux GoArch:amd64}
```

## golang 版本
* go version 1.6.15
