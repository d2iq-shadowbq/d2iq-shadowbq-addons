# Custom Addon and Registry for Ksphere

You will find the following directories here:

`addons/` - containing the actual manifests for addon resources
`deployments/` - containing the default addons depending on the Kubernetes version
`metadata/` - containing static metadata for the addons in addons/
`test/` - containing integration tests for the addons in addons/

## There are steps to take a helm chart to an addon on. 

Let's explore how to do this:

* https://github.com/mesosphere/kubeaddons
* https://raw.githubusercontent.com/helm/charts/b0f9cb2d7af822e0031f632f2faa0cbb53167770/stable/metallb/values.yaml
* https://github.com/mesosphere/kubernetes-base-addons/blob/master/addons/metallb/0.8.x/metallb-1.yaml
* https://github.com/mesosphere/kubeaddons-kommander/blob/master/addons/kommander/1.0.x/kommander.yaml

## Proper Addon Demo

* https://github.com/mesosphere/kubeaddons-demo

## Existing Addon Demo

* https://github.com/mesosphere/kubernetes-sre-addons/

## My Hello-world

* https://github.com/d2iq-shadowbq/container-hello-world-html-busybox
