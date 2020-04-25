# kdiscover
![Lint & build Golang project](https://github.com/mateimicu/kdiscover/workflows/Lint%20&%20build%20Golang%20project/badge.svg?branch=master)

! This is in pre-release status, no build, support is offered

A cli application used for discovering all K8S clusters that it can and importing them in kubeconfig.

Currently it support EKS clusters but we plan to expand it to GKE, AKS and maybe others.


## ToDo

- [x] allow for templated alias for the cluster name (give access to region, partition, cluster name, cluster arn)
- [x] investigate maybe it is worth parsing the kubeconfig instead of executing another command
- [x] CleanUp comments. print statements
- [x] prepare a ci pipeline
- [ ] add `aws` namespace in the CLI tree
- [ ] add tests for important parts and expecially some integration tests
- [ ] refactor modules (move from cmd to internals and add a better structure to internals)
- [ ] prepare packages for brew to distribute this project (and maybe others)
- [ ] prepare a cd pipeline (proabably build and publish artefacts)
- [ ] add documentation to the readme
- [ ] add GKE support
