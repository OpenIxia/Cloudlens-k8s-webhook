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