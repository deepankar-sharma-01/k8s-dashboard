# jweToken Cookie Setter for Kubernetes Dashboard

Sets the JWE Token Cookie to enable seamless access to kubernetes dashboard without exposing the JWT Token

To apply the ingress rule, run
```shell
kubectl apply -f cookie-setter-unified.yaml -n kubernetes-dashboard
```

`Note: The yaml assumes ingress class to be nginx. In case of a different ingress class, update the manifest accordingly`