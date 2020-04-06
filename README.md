# Pact-broker
This repository contains the pact broker template for openshift and Kubernetes(Please edit neccessory field for k8's)

1. Create pact-broker project/namespace.
2. Apply the persistent volume to pact-broker project.
  
    ```oc apply -f pv.yaml -n pact-broker```
  
3. Now apply the template to pact-broker project/namespace.

    ```oc apply -f template.yaml -n pact-broker```
