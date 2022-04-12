# OPA Gatekeeper Demo

## Getting started

1. Make sure you have already installed the Gatekeeper Operator in your cluster.
2. Install the bundle in your kubernetes using `kubectl` or the `oc` cli:

```sh
    cd opa-gatekeeper-demo

    # to add the only the OPA templates
    kubectl apply -k templates

    # to add only the OPA constraints
    kubectl apply -k constraints
```