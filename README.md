# kubernetes-vulnerabilities

Security vulnerabilities of Kubernetes.

Each file in the cve folder contains CVEs for a specific component of kubernetes:

- kubectl: vulnerabilities in the kubectl command-line
- kubelet: vulnerabilities in the kubelet node agent
- kubernetes: any vulnerability that requires an upgrade of kubernetes itself
- linux-kernel: kubernetes-related vulnerabilities that stem from the node OS

Each CVE must have one of the following fields:

- FixedIn: patch numbers that fix each vulnerable minor version (higher versions are assumed fixed)
- ExistsIn: a list of vulnerable versions (ranges or versions)

FirstVulnerableVersion is the first version that exposed this vulnerability.
