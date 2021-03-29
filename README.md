# Clubhouse Logs
Clubhouse Call Logs and Notes about interesting chats with interesting people.

## 29/03/21: Bleeding Edge Kubernetes Projects Conversation
- [K8Spin](https://k8spin.cloud)
  - Operator to solve Multi Tenancy inside a Kubernetes Cluster
  - Written in Python (Operator and Webhooks listener)
    - Uses [CertManager](https://github.com/jetstack/cert-manager) for webhooks 
  - 3 CRDs: Organization, Tenant, Space
  - [Python Kubernetes Operator Framework](https://github.com/nolar/kopf)

## 22/03/21: Bleeding Edge Kubernetes Projects Conversation
- [Crossplane](http://crossplane.io)
  - [Crossplane Providers]( https://crossplane.io/docs/v1.1/contributing/provider_development_guide.html)
  - [Extending Crossplane Provider template](https://github.com/crossplane/provider-template)
  - [Contrib Repositories](https://github.com/crossplane-contrib)
  - [Introduction to Crossplane - Youtube](https://www.youtube.com/watch?v=c_ZU8ZxR00E)
  - [Crossplane Kubernetes Podcast from Google](https://podcasts.google.com/feed/aHR0cHM6Ly9rdWJlcm5ldGVzcG9kY2FzdC5jb20vZmVlZHMvYXVkaW8ueG1s/episode/aHR0cHM6Ly9rdWJlcm5ldGVzcG9kY2FzdC5jb20vZXBpc29kZXMvS1BmR2VwMTQxLm1wMw?hl=en-GB&ved=2ahUKEwi1iYSj48TvAhVvaRUIHZIfCLYQjrkEegQIBhAF&ep=6)
  - [Crossplane vs terraform](https://blog.crossplane.io/crossplane-vs-terraform/)
  - [Crossplane community day](https://events.linuxfoundation.org/crossplane-community-day-europe/)


## 15/03/21: Bleeding Edge Kubernetes Projects Conversation
- [Keptn](http://keptn.sh) -> Delivery and deployment checking, with remediation and based on cloudevents
- [https://kapitan.dev](http://kaptain.dev) -> Templating engine
- [kubectl passman](https://github.com/chrisns/kubectl-passman) -> password manager integration for KubeCtl
- [cosign](https://github.com/sigstore/cosign) -> Signing container images


## 8/03/21: Bleeding Edge Kubernetes Projects Conversation
- RSocket.io in Kubernetes
  - What is RSocket? 
    -   https://rsocket.io
    -   https://www.infoq.com/news/2018/10/rsocket-facebook/
    -   https://www.infoq.com/presentations/rsocket-cloud-native/
  - How is that going to work in Kubernetes?
  - Who is running it on K8s?
- Operators:
  - https://kudo.dev
  - https://github.com/operator-framework/operator-sdk
  - https://github.com/kubernetes-sigs/kubebuilder
  - https://cloudnativetoolkit.dev
  - Kubernetes Patterns: free ebook - chapter on operator
  - Programming Kubernetes Book.

## 1/03/21: Bleeding Edge Kubernetes Projects Conversation

**Scaling/Serverless**
- [Knative Serving](https://knative.dev/docs/serving/)
- [KEDA](https://keda.sh) 

**MLOps** 
- [KubeFlow](https://www.kubeflow.org)
- [KFServing](https://github.com/kubeflow/kfserving)

**Security and Suply Chain**
- [In Toto](github.com/in-toto/in-toto)
- [Kubernetes Simulator](https://github.com/kubernetes-simulator/simulator)
- [Traitor](https://github.com/liamg/traitor)

**Integration**
- [CloudEvents](http://cloudevents.io)
  - [TriggerMesh Bumblebee](https://github.com/triggermesh/bumblebee)

