## Cloudlens Webhook
Author: Michael Wan

### Overview
A Golang Kubernetes admissions control webhook server

### Dependencies
This project requires the following Golang dependencies:
- Yaml (github.com/ghodss/yaml)
- Glog (github.com/golang/glog)
- k8s.io/api/admission/v1beta1
- k8s.io/api/admissionregistration/v1beta1
- k8s.io/api/core/v1
- k8s.io/apimachinery/pkg/apis/meta/v1
- k8s.io/apimachinery/pkg/runtime
- k8s.io/apimachinery/pkg/runtime/serializer
- k8s.io/kubernetes/pkg/apis/core/v1

### Building Image
Running the build script will push the image to Docker under michawan/sidecar-injector

The webhook image has already been built and is currently hosted at michawan/sidecar-injector on the Docker hub