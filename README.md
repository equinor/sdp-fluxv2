# sdp-fluxv2


### Inspiration/template
We used this repo [fluxcd/flux2-kustomize-helm-example](https://github.com/fluxcd/flux2-kustomize-helm-example) as inspiration and as a template for how to structure our new Flux v2 repo.


### External DNS
For enabling cert-manager we also need external-dns to be able to communicate with our services. 
We use the guide as described [here](https://github.com/kubernetes-sigs/external-dns/blob/master/docs/tutorials/azure.md#managed-identity-using-aks-kubelet-identity). 
Managed Identity and Azure DNS Zone is created using Bicep.