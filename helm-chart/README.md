# block-buster-helm-app

1. This repo contains an helm artefact which is linked to a repo in GitHub. 
2. This is used for FluxCD Demo.
3. Chart Name - `block-buster-helm-app`
4. URL - `https://swagatam04.github.io/block-buster-helm-app`
5. Container Image - `swagatam04/block-buster-dev:7.6.0`

### Sample values.yaml
```yaml
replicaCount: 1

service:
  type: NodePort
  nodePort: 30006

namespace:
  name: 6-demo
  
labels:
  app:
    name: block-buster
    version: 7.6.0
    env: dev
```
