<!-- ABOUT THE PROJECT -->
## Kubernetes GitOps workflow with Argo CD

Argo CD repository to deploy Kubernetes applications in my homelab with security in mind.

### Open Source Tools Used
* [Argo CD](https://argo-cd.readthedocs.io/en/stable/)
* [Helm](https://helm.sh/)
* [Kustomize](https://kustomize.io/)
* [Sealed Secrets](https://github.com/bitnami-labs/sealed-secrets)
* [Helm Secrets](https://github.com/jkroepke/helm-secrets)
* [SOPS](https://github.com/mozilla/sops)

### Applications deployed
* [actions-runner-controller](https://github.com/actions-runner-controller/actions-runner-controller)
* [grafana](https://grafana.com/)
* [prometheus](https://prometheus.io/)
* [vault](https://www.vaultproject.io/)
* [harbor](http://harbor.io/)
* [cloudflared](https://github.com/cloudflare/cloudflared)

### Related Repositories
* [ansible-homelab](https://github.com/wilinger/ansible-homelab)
* [terraform-homelab](https://github.com/wilinger/terraform-homelab)

### To do write ups
* Encrypting Secrets with Sealed Secrets
* Encrypting Helm values with Helm Secrets and SOPS
* Harbor self hosted registry with container vulnerability scanning
* Secure tunnel and Zero-trust application access with cloudflared
* RBAC
* Network policies
* OPA/Gatekeeper/Kyverno policy as code
* Committing secrets prevention and detection

