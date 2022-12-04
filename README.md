---
page_type: sample
languages:
- javascript
- nodejs
name: "Kubernetes example pipeline"
description: "Example of using kubernetes for automatic pull request review deployments"
products:
- azure
- vs-code
- kubernetes
---

# Example of using kubernetes in a pipeline

This repository is an example of using kubernetes in a build pipeline to
deploy app revisions for each pull request.

There's lots of ways to do this and this just an example.
Theres better and more elegant ways so do some extra research!
Helm charts would be one place to start researching to make the kubernetes deployment more elegant.

The example application for this was borrowed from https://github.com/Azure-Samples/js-e2e-express-server