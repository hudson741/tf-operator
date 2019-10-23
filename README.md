# K8s Custom Resource and Operator For TensorFlow jobs

[![Build Status](https://travis-ci.org/kubeflow/tf-operator.svg?branch=master)](https://travis-ci.org/kubeflow/tf-operator)
[![Coverage Status](https://coveralls.io/repos/github/kubeflow/tf-operator/badge.svg?branch=master)](https://coveralls.io/github/kubeflow/tf-operator?branch=master)
[![Go Report Card](https://goreportcard.com/badge/github.com/kubeflow/tf-operator)](https://goreportcard.com/report/github.com/kubeflow/tf-operator)


## 二次开发记录

* 更改tf-operator对kube-batch的依赖为0.1 改成0.2

* 增加tfjob的ttl时间，如果目标资源没有设置ttl，则给与设置ttl时间10分钟

* 实现对tfjob对分片索引，mount子路径自动发现



## Quick Links

* [Prow test dashboard](https://k8s-testgrid.appspot.com/sig-big-data)
* [Prow jobs dashboard](https://prow.k8s.io/?repo=kubeflow%2Ftf-operator)
* [Argo UI for E2E tests](http://testing-argo.kubeflow.org)

## Overview

TFJob provides a Kubernetes custom resource that makes it easy to
run distributed or non-distributed TensorFlow jobs on Kubernetes.

Please refer to the [user guide](https://www.kubeflow.org/docs/guides/components/tftraining/) for more information.

## Contributing

Please refer to the [developer_guide](developer_guide.md)

## Change Log

Please refer to [CHANGELOG](CHANGELOG.md)

## Community

This is a part of Kubeflow, so please see [readme in kubeflow/kubeflow](https://github.com/kubeflow/kubeflow#get-involved) to get in touch with the community.
