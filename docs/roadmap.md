# Roadmap

## 2020.09

The 2020.09 release contains [klever-model-registry][] and [ormb][].

[klever-model-registry][] contains one long-running backend server, one Kubernetes CRD operator, one dashboard.

[klever-model-registry][] features:

- Manage ML models
- Keep track of ML models' hyperparameters and so on to help decision makers
- Convert models between different formats
- Extract signatures for the given models
- Serve the simple models ( single model, without inference graph support ) using Triton Inference Server
- Support uploading models from the dashboard
- Get model conversion/extraction job logs and events

[ormb][] contains two executive programs.

[ormb][] features:

- Save, export models from/to local filesystem cache
- Push, pull models from/to remote registry

## 2020.11

The 2020.11 release contains [klever-model-registry][] and [ormb][].

[klever-model-registry][] contains one long-running backend server, one Kubernetes CRD operator, one dashboard.

[klever-model-registry][] new features:

- Support multi-users
- Provide offline unified batch inference interface
- Support traffic management for model inference

[ormb][] contains two executive programs.

[ormb][] new features:

- Support TLS verification
- Validate model directory layout for the given format

## 2021.01

The 2020.01 release contains [klever-model-registry][] and [ormb][].

[klever-model-registry][] contains one long-running backend server, one Kubernetes CRD operator, one dashboard.

[klever-model-registry][] new features:

- Support model compression
- Support edge deployment

[ormb][] contains two executive programs.

[ormb][] new features:

- Support README addition layer

We may start working on training in this release.

[klever-model-registry]: https://github.com/kleveross/klever-model-registry
[ormb]: https://github.com/kleveross/ormb
